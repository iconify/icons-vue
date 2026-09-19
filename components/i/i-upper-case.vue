<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m077kqbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":735};
const content = `<path class="m077kqbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:i-upper-case" /></template>
