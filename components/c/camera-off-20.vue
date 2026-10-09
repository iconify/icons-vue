<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbi0yub_m.css';
import '../../css/m/msu5rib1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pbi0yub_m"/><path class="msu5rib1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camera-off-20" /></template>
