<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyvh6kk2s.css';
import '../../css/j/jk43hwbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nyvh6kk2s"/><path class="jk43hwbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flowchart-20-bold" /></template>
