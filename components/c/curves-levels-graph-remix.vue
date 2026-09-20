<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-p8twb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d-p8twb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:curves-levels-graph-remix" /></template>
