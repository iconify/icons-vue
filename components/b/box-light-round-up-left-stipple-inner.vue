<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg_q-fb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="fg_q-fb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-up-left-stipple-inner" /></template>
