<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o44bfh3jr.css';
import '../../css/q/qr4ochb5c.css';
import '../../css/q/qvra2koks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="o44bfh3jr"/><path class="qr4ochb5c wm-s"/><path class="qvra2koks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-off-duo" /></template>
