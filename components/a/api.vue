<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usyw0nb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="usyw0nb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:api" /></template>
