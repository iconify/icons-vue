<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt-7v1wio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xt-7v1wio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:globe" /></template>
