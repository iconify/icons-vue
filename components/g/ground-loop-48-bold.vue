<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbgn9e5js.css';
import '../../css/t/tjum5_rgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nbgn9e5js"/><path class="tjum5_rgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ground-loop-48-bold" /></template>
