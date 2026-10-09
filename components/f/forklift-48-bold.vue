<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctpcvf1md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ctpcvf1md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forklift-48-bold" /></template>
