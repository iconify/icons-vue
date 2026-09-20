<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5-epbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ca5-epbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:button-power-1" /></template>
