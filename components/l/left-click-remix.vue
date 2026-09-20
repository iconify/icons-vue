<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scf1s7c6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="scf1s7c6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:left-click-remix" /></template>
