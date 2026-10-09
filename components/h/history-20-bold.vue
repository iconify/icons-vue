<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mubd4760u.css';
import '../../css/h/hfy0htikh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mubd4760u"/><path class="hfy0htikh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:history-20-bold" /></template>
