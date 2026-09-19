<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/ss97y7h8n.css';
import '../../css/q/q2kel5-0b.css';
import '../../css/f/f65fcelrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ss97y7h8n"/><path class="q2kel5-0b"/><path class="f65fcelrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:kettle-01" /></template>
