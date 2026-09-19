<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4bwlab3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x4bwlab3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:humidity" /></template>
