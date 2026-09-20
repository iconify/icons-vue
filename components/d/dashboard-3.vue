<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp36jgbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fp36jgbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:dashboard-3" /></template>
