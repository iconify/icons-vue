<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2pnz7bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="s2pnz7bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:lightbulb-on" /></template>
