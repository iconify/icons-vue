<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qku5pfb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="qku5pfb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-trending-stroke-12" /></template>
