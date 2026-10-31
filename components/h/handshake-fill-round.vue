<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t06y_mbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t06y_mbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:handshake-fill-round" /></template>
