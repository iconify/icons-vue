<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdlxyvhkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdlxyvhkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-laugh-squint" /></template>
