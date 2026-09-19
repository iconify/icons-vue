<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k61l-wb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k61l-wb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:intent-request-scale-out" /></template>
