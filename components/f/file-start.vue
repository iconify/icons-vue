<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbigfv4ml.css';
import '../../css/z/zdyt6ubsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbigfv4ml"/><path class="zdyt6ubsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-start" /></template>
