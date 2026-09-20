<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4bb7ybtz.css';
import '../../css/x/xns9x_bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4bb7ybtz"/><path class="xns9x_bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-pytorch-open" /></template>
