<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9pd17xhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="d9pd17xhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:digital9" /></template>
