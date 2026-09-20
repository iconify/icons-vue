<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz3fx8zga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zz3fx8zga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-fit-to-height-square-remix" /></template>
