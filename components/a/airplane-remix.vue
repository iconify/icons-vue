<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw65e4biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xw65e4biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:airplane-remix" /></template>
