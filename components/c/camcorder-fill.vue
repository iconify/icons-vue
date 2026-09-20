<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2cq-bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx2cq-bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-fill" /></template>
