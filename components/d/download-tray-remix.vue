<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwm40bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qnwm40bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:download-tray-remix" /></template>
