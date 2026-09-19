<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_60jfce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xc_60jfce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:chevron-circle-left" /></template>
