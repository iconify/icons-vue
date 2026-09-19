<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o88u_xb9d.css';
import '../../css/r/r7xl8ggtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o88u_xb9d"/><path class="r7xl8ggtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-hazard-filled" /></template>
