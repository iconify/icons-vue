<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-vex1-ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="h-vex1-ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:eraser" /></template>
