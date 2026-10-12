<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqyl277ii.css';
import '../../css/m/mczjewvdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qqyl277ii"/><path class="mczjewvdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:bot-sparkle-stroke-20" /></template>
