<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv4old3dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hv4old3dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:building-construction" /></template>
