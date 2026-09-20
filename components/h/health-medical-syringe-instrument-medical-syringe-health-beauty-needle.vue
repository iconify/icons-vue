<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycor5295j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ycor5295j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:health-medical-syringe-instrument-medical-syringe-health-beauty-needle" /></template>
