<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjbg4zucq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cjbg4zucq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-horizontal-expand-expand-resize-bigger-horizontal-smaller-size-arrow-arrows-big" /></template>
