<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wih5c8o4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="wih5c8o4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-right-horizontal-stipple-up" /></template>
