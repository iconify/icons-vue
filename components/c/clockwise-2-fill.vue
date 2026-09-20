<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkss39bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkss39bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:clockwise-2-fill" /></template>
