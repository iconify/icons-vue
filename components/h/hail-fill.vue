<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im5_q7b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="im5_q7b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hail-fill" /></template>
