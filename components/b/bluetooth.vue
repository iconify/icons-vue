<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swfgeb0ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="swfgeb0ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:bluetooth" /></template>
