<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp052t5vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dp052t5vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cut" /></template>
