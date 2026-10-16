<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzxt0mswz.css';
import '../../css/h/htyx_ybsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzxt0mswz"/><path class="htyx_ybsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gas-compressor-48-bold" /></template>
