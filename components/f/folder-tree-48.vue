<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1p_9z-6l.css';
import '../../css/z/z3rbxgblu.css';
import '../../css/j/j80farb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1p_9z-6l"/><path class="z3rbxgblu"/><path class="j80farb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-tree-48" /></template>
