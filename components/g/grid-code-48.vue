<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_z99bhx.css';
import '../../css/i/i7t6r5bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="i7t6r5bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:grid-code-48" /></template>
