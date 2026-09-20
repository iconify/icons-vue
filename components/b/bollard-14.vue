<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3375dbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="w3375dbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:bollard-14" /></template>
