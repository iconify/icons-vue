<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7qx85bwi.css';
import '../../css/e/ewkztrbus.css';
import '../../css/x/x4pwz20fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g7qx85bwi"/><path class="ewkztrbus"/><path class="x4pwz20fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:calendar-x-20-bold" /></template>
