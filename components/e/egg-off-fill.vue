<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgu54ybmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgu54ybmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:egg-off-fill" /></template>
