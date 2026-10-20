<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r20d5fbva.css';
import '../../css/o/o08gbrx6h.css';
import '../../css/c/cvogzw0ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r20d5fbva"/><path class="o08gbrx6h"/><path class="cvogzw0ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:joystick-48-bold" /></template>
