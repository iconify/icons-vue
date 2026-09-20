<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb62_obsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sb62_obsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:gif-format-remix" /></template>
