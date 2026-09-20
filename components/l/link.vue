<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjk242bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yjk242bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:link" /></template>
