<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i37phhb_v.css';
import '../../css/u/uw6sq-v3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i37phhb_v"/><path class="uw6sq-v3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-paint-roll" /></template>
