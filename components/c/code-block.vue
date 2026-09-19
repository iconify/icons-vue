<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0j4x9bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n0j4x9bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:code-block" /></template>
