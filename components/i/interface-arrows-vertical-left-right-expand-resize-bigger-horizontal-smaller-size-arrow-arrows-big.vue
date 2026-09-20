<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue03v71pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ue03v71pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-vertical-left-right-expand-resize-bigger-horizontal-smaller-size-arrow-arrows-big" /></template>
