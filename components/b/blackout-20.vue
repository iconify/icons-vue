<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg31mwb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rg31mwb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blackout-20" /></template>
