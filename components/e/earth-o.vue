<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4eowcbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="u4eowcbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:earth-o" /></template>
