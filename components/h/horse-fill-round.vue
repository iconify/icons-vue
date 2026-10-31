<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq2ci_q3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq2ci_q3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:horse-fill-round" /></template>
