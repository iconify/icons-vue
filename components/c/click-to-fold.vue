<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh40-cbre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zh40-cbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:click-to-fold" /></template>
