<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgj5w-y0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="qgj5w-y0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:flash-3-flat" /></template>
