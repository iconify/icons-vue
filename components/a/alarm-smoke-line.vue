<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-9w2_p5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-9w2_p5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alarm-smoke-line" /></template>
