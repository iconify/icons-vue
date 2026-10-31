<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4g4k4bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4g4k4bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clock-gloss" /></template>
