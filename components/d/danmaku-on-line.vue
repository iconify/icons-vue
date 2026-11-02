<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbclqhbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbclqhbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-on-line" /></template>
