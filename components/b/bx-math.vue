<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyg2p5f5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyg2p5f5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-math" /></template>
