<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qguk79b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qguk79b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:horizontal-toggle-button-remix" /></template>
