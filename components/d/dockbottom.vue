<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_gb2ybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_gb2ybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:dockbottom" /></template>
