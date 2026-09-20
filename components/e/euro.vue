<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnh-evkbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dnh-evkbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:euro" /></template>
