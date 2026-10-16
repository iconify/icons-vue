<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzxt0mswz.css';
import '../../css/f/fnuad0uhx.css';
import '../../css/k/kzyi2ibpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzxt0mswz"/><path class="fnuad0uhx"/><path class="kzyi2ibpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-compressor-48-bold" /></template>
