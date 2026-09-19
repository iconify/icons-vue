<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh_k5d__w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uh_k5d__w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chart-lollipop" /></template>
