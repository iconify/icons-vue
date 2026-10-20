<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_z99bhx.css';
import '../../css/h/hn78hr1xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="hn78hr1xu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-sparkle-48" /></template>
