<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipp9v_bkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipp9v_bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-lock-1" /></template>
