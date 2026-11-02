<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4rkire3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4rkire3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-ai-fill" /></template>
