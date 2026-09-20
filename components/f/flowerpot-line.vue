<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc_q4r-ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_q4r-ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flowerpot-line" /></template>
