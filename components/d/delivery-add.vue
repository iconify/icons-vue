<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3frg7bxu.css';
import '../../css/y/yr77b-b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w3frg7bxu"/><path class="yr77b-b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:delivery-add" /></template>
