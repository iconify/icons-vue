<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5q_egfpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5q_egfpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:forklift-line" /></template>
