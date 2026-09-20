<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmz4urbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fmz4urbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:layout-window-1" /></template>
