<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7eipv1zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q7eipv1zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:figma-remix" /></template>
