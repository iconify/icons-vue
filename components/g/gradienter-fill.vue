<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up7bxb_fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up7bxb_fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gradienter-fill" /></template>
