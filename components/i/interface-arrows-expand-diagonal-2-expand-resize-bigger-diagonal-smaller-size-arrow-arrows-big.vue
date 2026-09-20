<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu50glron.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uu50glron"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-expand-diagonal-2-expand-resize-bigger-diagonal-smaller-size-arrow-arrows-big" /></template>
