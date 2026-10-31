<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxkkocc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxkkocc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-8-fill-round" /></template>
