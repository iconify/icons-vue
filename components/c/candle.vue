<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa2jpwbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xa2jpwbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:candle" /></template>
