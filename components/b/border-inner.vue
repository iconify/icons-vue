<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvzi22bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvzi22bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:border-inner" /></template>
