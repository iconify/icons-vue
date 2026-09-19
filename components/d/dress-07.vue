<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p8noaabtb.css';
import '../../css/x/xfkr8aboy.css';
import '../../css/m/m247a-91k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p8noaabtb"/><path class="xfkr8aboy"/><path class="m247a-91k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dress-07" /></template>
