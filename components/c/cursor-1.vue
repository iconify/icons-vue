<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqszbtbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqszbtbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-1" /></template>
