<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy1azp4oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="vy1azp4oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-up-left-stipple" /></template>
