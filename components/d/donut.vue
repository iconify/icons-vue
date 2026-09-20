<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mii129bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mii129bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:donut" /></template>
