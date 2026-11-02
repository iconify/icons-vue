<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f30f44sse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f30f44sse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:airdrop-fill" /></template>
