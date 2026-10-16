<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1pz25ahp.css';
import '../../css/z/z0v5_fbef.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j1pz25ahp"/><path class="z0v5_fbef"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:invoice-paid-20-bold" /></template>
