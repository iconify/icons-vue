<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz42h1bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wz42h1bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle-gate-with-battlements-and-spires" /></template>
