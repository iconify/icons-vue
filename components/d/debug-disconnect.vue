<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fte7bcbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fte7bcbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-disconnect" /></template>
