<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg517acka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cg517acka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:brightness-1-remix" /></template>
