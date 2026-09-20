<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4wuv_o1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f4wuv_o1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deepseek-light" /></template>
