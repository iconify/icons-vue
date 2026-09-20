<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2p1o2bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2p1o2bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-angle-off" /></template>
