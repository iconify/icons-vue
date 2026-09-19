<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9umdbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9umdbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:alarm-off" /></template>
