<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_u9s4y3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i_u9s4y3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cc-text-in-tv-screen" /></template>
