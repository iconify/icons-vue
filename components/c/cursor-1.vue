<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3-ktby_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l3-ktby_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cursor-1" /></template>
