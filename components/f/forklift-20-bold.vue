<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv82_wb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mv82_wb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forklift-20-bold" /></template>
