<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjxdntixj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mjxdntixj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:button-record-1-remix" /></template>
