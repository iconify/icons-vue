<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw-xedbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yw-xedbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:cloud-showers-heavy" /></template>
