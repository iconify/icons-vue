<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3l36it8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d3l36it8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-block-remix" /></template>
