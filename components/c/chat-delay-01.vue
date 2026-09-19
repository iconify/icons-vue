<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/ugrlbnbrf.css';
import '../../css/q/qdt7c407j.css';
import '../../css/l/lsl9z7beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ugrlbnbrf"/><path class="qdt7c407j"/><path class="lsl9z7beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chat-delay-01" /></template>
