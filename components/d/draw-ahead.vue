<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_-waucfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_-waucfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:draw-ahead" /></template>
