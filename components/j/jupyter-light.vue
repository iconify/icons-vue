<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1mhdw-bn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x1mhdw-bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jupyter-light" /></template>
