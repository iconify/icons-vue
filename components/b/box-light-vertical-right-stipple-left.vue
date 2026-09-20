<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv2lx-mpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bv2lx-mpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-right-stipple-left" /></template>
