<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-vbe6pbb.css';
import '../../css/h/h_wxks0bq.css';
import '../../css/f/fcaf33b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-vbe6pbb"/><path class="h_wxks0bq"/><path class="fcaf33b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-line-duotone" /></template>
