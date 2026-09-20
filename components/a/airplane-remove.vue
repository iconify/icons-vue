<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do4-2pbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do4-2pbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-remove" /></template>
