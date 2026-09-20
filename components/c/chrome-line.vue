<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m56sstc-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m56sstc-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chrome-line" /></template>
