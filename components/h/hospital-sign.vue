<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqfgfb1ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hqfgfb1ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hospital-sign" /></template>
