<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w64ql4i5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w64ql4i5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:header-3-20" /></template>
