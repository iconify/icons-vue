<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-4h1bclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="d-4h1bclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:face-like" /></template>
