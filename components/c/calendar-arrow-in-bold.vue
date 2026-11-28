<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ourw59bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ourw59bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-arrow-in-bold" /></template>
