<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4t1tb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh4t1tb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:cross" /></template>
