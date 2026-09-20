<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l99uu10zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l99uu10zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:camera-1-remix" /></template>
