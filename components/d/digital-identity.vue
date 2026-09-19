<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p37_k_s9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p37_k_s9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:digital-identity" /></template>
