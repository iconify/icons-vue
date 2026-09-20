<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3ayd58ao.css';
import '../../css/k/ki6lx60di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3ayd58ao"/><path class="ki6lx60di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:folder-open" /></template>
