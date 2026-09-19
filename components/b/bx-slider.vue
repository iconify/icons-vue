<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy092wb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy092wb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-slider" /></template>
