<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p77k6zh-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="p77k6zh-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-left-right" /></template>
