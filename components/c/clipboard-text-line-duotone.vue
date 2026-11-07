<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/urc5ue4jr.css';
import '../../css/x/x_757hbgu.css';
import '../../css/d/d5t0b286k.css';
import '../../css/m/my5268blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="urc5ue4jr"/><path class="x_757hbgu"/><path class="d5t0b286k"/><path class="my5268blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-text-line-duotone" /></template>
