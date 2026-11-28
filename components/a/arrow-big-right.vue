<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh88yjbtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh88yjbtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:arrow-big-right" /></template>
