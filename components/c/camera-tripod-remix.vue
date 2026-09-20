<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sagha-81g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sagha-81g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-tripod-remix" /></template>
