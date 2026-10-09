<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m810bccve.css';
import '../../css/s/s4bn_vbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m810bccve"/><path class="s4bn_vbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-island-48-bold" /></template>
