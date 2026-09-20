<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh95nccwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh95nccwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-turn-right-down-expressive" /></template>
