<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuo_0fbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuo_0fbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bus-round" /></template>
