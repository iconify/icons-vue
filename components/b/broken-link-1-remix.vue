<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpxoxl2mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vpxoxl2mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:broken-link-1-remix" /></template>
