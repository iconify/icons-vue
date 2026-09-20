<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxl-ikbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qxl-ikbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-text" /></template>
