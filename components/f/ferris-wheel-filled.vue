<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4xr16b6e.css';
import '../../css/t/tq6omth6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4xr16b6e"/><path class="tq6omth6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ferris-wheel-filled" /></template>
