<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykhcx6d8l.css';
import '../../css/w/ww40tqben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ykhcx6d8l"/><path class="ww40tqben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cloud-auditing" /></template>
