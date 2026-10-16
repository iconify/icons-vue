<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is2wtacnu.css';
import '../../css/w/wqs95_b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="is2wtacnu"/><path class="wqs95_b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-pie-slice-20-bold" /></template>
