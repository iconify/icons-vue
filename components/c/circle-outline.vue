<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0_1vs7im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w0_1vs7im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:circle-outline" /></template>
