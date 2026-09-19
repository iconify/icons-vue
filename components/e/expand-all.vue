<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyl2igb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gyl2igb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:expand-all" /></template>
