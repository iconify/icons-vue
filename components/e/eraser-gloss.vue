<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmk-q3y2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmk-q3y2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:eraser-gloss" /></template>
