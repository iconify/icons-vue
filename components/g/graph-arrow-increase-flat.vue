<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3b1-vbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q3b1-vbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:graph-arrow-increase-flat" /></template>
