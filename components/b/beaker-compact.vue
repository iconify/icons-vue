<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkhkx2bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="hkhkx2bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:beaker-compact" /></template>
