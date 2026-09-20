<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgukkub9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xgukkub9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:battery-empty" /></template>
