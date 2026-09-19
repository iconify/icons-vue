<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krvn_ccod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="krvn_ccod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:categories" /></template>
