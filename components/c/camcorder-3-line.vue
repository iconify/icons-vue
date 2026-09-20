<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf2faab1e.css';
import '../../css/c/czl4vwb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf2faab1e"/><path class="czl4vwb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camcorder-3-line" /></template>
