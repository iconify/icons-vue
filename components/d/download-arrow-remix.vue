<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfl_0pbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mfl_0pbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:download-arrow-remix" /></template>
