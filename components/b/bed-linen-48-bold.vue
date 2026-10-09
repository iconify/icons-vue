<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xe70pmbug.css';
import '../../css/a/aordspgcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xe70pmbug"/><path class="aordspgcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-linen-48-bold" /></template>
