<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_7is9beq.css';
import '../../css/s/sk8h-pxpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q_7is9beq"/><path class="sk8h-pxpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-down-left-20" /></template>
