<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fir_e1b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fir_e1b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dot-grid-fill" /></template>
