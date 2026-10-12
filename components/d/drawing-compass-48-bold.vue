<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5hh0bxr.css';
import '../../css/c/cu1d12b6p.css';
import '../../css/d/d5sbbcb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="py5hh0bxr"/><path class="cu1d12b6p"/><path class="d5sbbcb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drawing-compass-48-bold" /></template>
