<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cszoybbgj.css';
import '../../css/x/xaknxzbmx.css';
import '../../css/m/m07y7fbsy.css';
import '../../css/d/dp4gjjb8w.css';
import '../../css/h/h-htocc-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cszoybbgj"/><path class="xaknxzbmx"/><path class="m07y7fbsy"/><path class="dp4gjjb8w"/><path class="h-htocc-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-plugged-20-bold" /></template>
