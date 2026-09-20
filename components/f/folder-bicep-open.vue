<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1o01ybqh.css';
import '../../css/w/w085iof8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1o01ybqh"/><path class="w085iof8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-bicep-open" /></template>
