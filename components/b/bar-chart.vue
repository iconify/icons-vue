<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk5joxc5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zk5joxc5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bar-chart" /></template>
