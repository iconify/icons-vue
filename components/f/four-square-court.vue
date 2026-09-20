<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvy-1ccnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yvy-1ccnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-square-court" /></template>
