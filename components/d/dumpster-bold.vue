<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txd9fd4nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="txd9fd4nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:dumpster-bold" /></template>
