<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6cv0ac1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6cv0ac1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:candle-filled" /></template>
