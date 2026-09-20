<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2bf_gb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2bf_gb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-2-line" /></template>
