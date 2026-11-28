<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynhp2xbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ynhp2xbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-clock-fill" /></template>
