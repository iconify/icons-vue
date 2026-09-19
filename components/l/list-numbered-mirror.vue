<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3x4476xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n3x4476xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list-numbered-mirror" /></template>
