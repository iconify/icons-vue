<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1m50d5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1m50d5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:flip-horizontal-arrow-1-solid" /></template>
