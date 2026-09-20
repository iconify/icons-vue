<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j96f-ebaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j96f-ebaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-horizontal-up-down-expand-resize-bigger-vertical-smaller-size-arrow-arrows-big" /></template>
