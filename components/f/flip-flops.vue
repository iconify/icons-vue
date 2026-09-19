<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm3uhnq1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hm3uhnq1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flip-flops" /></template>
