<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-1leoezv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d-1leoezv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:3d-coordinate-axis-remix" /></template>
