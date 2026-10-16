<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh-es2avx.css';
import '../../css/x/x8lr6rehc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xh-es2avx"/><path class="x8lr6rehc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-off-20-bold" /></template>
