<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm87n4bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bm87n4bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:comments" /></template>
