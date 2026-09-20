<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2d4_eb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2d4_eb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dual-sim-2-fill" /></template>
