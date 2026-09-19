<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p619a9b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p619a9b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:choose-item" /></template>
