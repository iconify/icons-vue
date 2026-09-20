<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywztcab3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ywztcab3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:calm-face-in-circle-outline" /></template>
