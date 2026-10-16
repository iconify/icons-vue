<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ob8sbdr.css';
import '../../css/k/kux8a1jyn.css';
import '../../css/a/aho46rbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w7ob8sbdr"/><path class="kux8a1jyn"/><path class="aho46rbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lidar-20-bold" /></template>
