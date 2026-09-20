<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4e6ccdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zh4e6ccdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compact-box-truck-with-box-peak" /></template>
