<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqs2jwb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqs2jwb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-line" /></template>
