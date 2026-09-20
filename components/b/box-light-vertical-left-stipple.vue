<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp6tc4bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lp6tc4bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-left-stipple" /></template>
