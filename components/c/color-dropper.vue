<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3x57yb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d3x57yb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:color-dropper" /></template>
