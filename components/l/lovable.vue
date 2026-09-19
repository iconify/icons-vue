<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynj4_2gt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yynj4_2gt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:lovable" /></template>
