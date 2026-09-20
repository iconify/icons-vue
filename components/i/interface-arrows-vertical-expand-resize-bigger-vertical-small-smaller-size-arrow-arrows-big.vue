<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdevb0p2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wdevb0p2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-vertical-expand-resize-bigger-vertical-small-smaller-size-arrow-arrows-big" /></template>
