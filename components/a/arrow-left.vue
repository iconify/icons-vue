<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so4ohuxyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="so4ohuxyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-left" /></template>
