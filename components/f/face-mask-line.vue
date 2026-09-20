<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2s21khxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s21khxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:face-mask-line" /></template>
