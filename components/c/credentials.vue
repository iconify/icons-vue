<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh9mnbc-e.css';
import '../../css/g/gibdywb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh9mnbc-e"/><path class="gibdywb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:credentials" /></template>
