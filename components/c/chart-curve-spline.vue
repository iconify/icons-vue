<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpcjoqb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zpcjoqb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-curve-spline" /></template>
