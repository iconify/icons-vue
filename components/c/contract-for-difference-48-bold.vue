<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pz3rxhk.css';
import '../../css/y/y6w07qbtw.css';
import '../../css/p/pfe8gjbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="y6w07qbtw"/><path class="pfe8gjbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:contract-for-difference-48-bold" /></template>
