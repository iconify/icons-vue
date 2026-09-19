<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgc4y1zlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgc4y1zlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-1-thin" /></template>
