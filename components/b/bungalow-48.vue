<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsfzl1bhj.css';
import '../../css/d/dtsd2ea6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rsfzl1bhj"/><path class="dtsd2ea6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bungalow-48" /></template>
