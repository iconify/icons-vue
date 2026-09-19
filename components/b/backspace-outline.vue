<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrbt_q4og.css';
import '../../css/p/pt8e8sjhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrbt_q4og"/><path class="pt8e8sjhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:backspace-outline" /></template>
