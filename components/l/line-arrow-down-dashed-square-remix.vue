<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3h7ejbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p3h7ejbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-down-dashed-square-remix" /></template>
