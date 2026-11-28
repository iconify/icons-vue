<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_b0ybb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_b0ybb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:darts" /></template>
