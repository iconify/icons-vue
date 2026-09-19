<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct5dzobis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ct5dzobis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-foundry-2" /></template>
