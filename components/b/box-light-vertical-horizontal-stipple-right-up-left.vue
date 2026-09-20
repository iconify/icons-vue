<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en_y3r5if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="en_y3r5if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-right-up-left" /></template>
