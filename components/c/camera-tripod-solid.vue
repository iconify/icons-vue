<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah666hbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ah666hbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-tripod-solid" /></template>
