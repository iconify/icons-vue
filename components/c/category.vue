<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qie1qfb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qie1qfb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:category" /></template>
