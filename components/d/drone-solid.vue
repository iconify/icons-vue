<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv322cbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zv322cbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:drone-solid" /></template>
