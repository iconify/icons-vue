<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feg7vxbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="feg7vxbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chess-knight" /></template>
