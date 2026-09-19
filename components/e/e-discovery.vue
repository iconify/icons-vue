<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dor8m7bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dor8m7bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:e-discovery" /></template>
