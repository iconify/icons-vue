<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pizot5u_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pizot5u_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:keyboard-remix" /></template>
