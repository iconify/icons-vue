<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ua393o__d.css';
import '../../css/p/pi73q5bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ua393o__d"/><path class="pi73q5bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cake-20-bold" /></template>
