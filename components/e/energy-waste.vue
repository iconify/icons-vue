<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tici9vb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tici9vb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:energy-waste" /></template>
