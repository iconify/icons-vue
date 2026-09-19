<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnb6xndjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="rnb6xndjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:filter-tilt-shift" /></template>
