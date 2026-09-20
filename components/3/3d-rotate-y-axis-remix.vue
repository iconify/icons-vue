<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c96sl1brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c96sl1brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-rotate-y-axis-remix" /></template>
