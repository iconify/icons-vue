<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm-dfbcsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm-dfbcsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-10-line" /></template>
