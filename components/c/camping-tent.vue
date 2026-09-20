<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8l-kygsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u8l-kygsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camping-tent" /></template>
