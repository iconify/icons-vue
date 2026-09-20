<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azzl-tb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="azzl-tb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-alert-triangle-1" /></template>
