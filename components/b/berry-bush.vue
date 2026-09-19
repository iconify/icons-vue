<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaej6lb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oaej6lb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:berry-bush" /></template>
