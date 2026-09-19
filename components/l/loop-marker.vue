<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fajg1w5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="fajg1w5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:loop-marker" /></template>
