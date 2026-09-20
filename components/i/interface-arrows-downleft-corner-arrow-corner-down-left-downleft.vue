<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o04t7ctoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="o04t7ctoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-downleft-corner-arrow-corner-down-left-downleft" /></template>
