<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctgdt-6yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ctgdt-6yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-stipple" /></template>
