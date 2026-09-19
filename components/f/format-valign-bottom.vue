<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw_r7wb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="vw_r7wb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-valign-bottom" /></template>
