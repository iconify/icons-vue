<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5uxynb9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w5uxynb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:balloon-solid" /></template>
