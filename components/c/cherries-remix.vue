<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am4viierx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="am4viierx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cherries-remix" /></template>
