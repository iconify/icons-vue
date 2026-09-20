<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfy61bqzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfy61bqzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-fill" /></template>
