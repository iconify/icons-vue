<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg1-ktdwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rg1-ktdwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:end-point-diamond-remix" /></template>
