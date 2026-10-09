<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw3xuy-8f.css';
import '../../css/l/ldri-y0et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fw3xuy-8f"/><path class="ldri-y0et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forward-48" /></template>
