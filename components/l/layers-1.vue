<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-71xacun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i-71xacun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:layers-1" /></template>
