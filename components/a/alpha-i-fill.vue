<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0xrnioja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="y0xrnioja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-i-fill" /></template>
