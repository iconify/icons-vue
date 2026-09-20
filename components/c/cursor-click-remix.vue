<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5dhwaboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d5dhwaboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cursor-click-remix" /></template>
