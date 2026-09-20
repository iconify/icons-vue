<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2pyy_bce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f2pyy_bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:coin-1" /></template>
