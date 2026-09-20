<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m63h_6bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m63h_6bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:line-arrow-rotate-left-2-remix" /></template>
