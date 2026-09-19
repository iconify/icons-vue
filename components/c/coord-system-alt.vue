<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug25vmbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ug25vmbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:coord-system-alt" /></template>
