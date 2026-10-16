<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3-ldu6ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3-ldu6ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bluetooth-connected-20-bold" /></template>
