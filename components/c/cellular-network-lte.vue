<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy4xbiqqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wy4xbiqqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cellular-network-lte" /></template>
