<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3xbb8-vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c3xbb8-vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-align-layers-1-design-layer-layers-pile-stack" /></template>
