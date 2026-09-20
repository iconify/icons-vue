<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz46q1bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz46q1bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:immersive-translate" /></template>
