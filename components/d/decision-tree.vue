<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8_76bc0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h8_76bc0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:decision-tree" /></template>
