<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oja1cermz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oja1cermz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hierarchy-line-3-remix" /></template>
