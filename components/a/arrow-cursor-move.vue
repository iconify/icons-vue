<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8a631bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q8a631bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:arrow-cursor-move" /></template>
