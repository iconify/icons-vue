<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn_m2bm7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_m2bm7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-pie-line" /></template>
