<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t44iphbtl.css';
import '../../css/x/xq-7rxmzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t44iphbtl"/><path class="xq-7rxmzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:box" /></template>
