<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnwr_1bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwr_1bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:draw-compass" /></template>
