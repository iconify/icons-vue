<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9ls55b_f.css';
import '../../css/n/n0np7fbxk.css';
import '../../css/j/j1y330bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o9ls55b_f"/><path class="n0np7fbxk"/><path class="j1y330bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:import-export-20" /></template>
