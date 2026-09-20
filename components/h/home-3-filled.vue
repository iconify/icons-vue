<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf01qzbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yf01qzbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-3-filled" /></template>
