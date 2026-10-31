<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cimfwhbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cimfwhbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gamepad-gloss" /></template>
