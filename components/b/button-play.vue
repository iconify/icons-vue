<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3t15vy2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="l3t15vy2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:button-play" /></template>
