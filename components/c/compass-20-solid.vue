<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgb4w9bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wgb4w9bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass-20-solid" /></template>
