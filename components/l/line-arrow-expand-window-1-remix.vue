<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiq7_wb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oiq7_wb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:line-arrow-expand-window-1-remix" /></template>
