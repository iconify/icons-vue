<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw_t0ebdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw_t0ebdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arc-browser-line" /></template>
