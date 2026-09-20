<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pacc4ybvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pacc4ybvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-move-left-2-remix" /></template>
