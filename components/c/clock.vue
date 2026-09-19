<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3eo2xxnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="m3eo2xxnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:clock" /></template>
