<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh6ubzb2y.css';
import '../../css/b/byjpcpbho.css';
import '../../css/h/h1p9bccth.css';
import '../../css/l/l_nf0hbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh6ubzb2y"/><path class="byjpcpbho"/><path class="h1p9bccth"/><path class="l_nf0hbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:food-drink-sushi" /></template>
