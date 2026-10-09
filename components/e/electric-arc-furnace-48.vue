<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lazjyk96p.css';
import '../../css/z/z8apakboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lazjyk96p"/><path class="z8apakboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-arc-furnace-48" /></template>
