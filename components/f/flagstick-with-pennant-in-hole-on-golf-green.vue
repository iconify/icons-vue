<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipiac7buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ipiac7buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagstick-with-pennant-in-hole-on-golf-green" /></template>
