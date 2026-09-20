<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulsl_sblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulsl_sblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-smile-3-line" /></template>
