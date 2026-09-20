<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_60tzip.css';
import '../../css/w/wyf5cbt8m.css';
import '../../css/y/yyz6j7bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xd_60tzip"/><path class="wyf5cbt8m"/><path class="yyz6j7bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-shrink-1" /></template>
