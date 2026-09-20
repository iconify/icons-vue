<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6k_3kb4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u6k_3kb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-horizontal-shrink-resize-shrink-bigger-horizontal-smaller-size-arrow-arrows-big" /></template>
