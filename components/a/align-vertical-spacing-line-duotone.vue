<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/ql8wzqa2k.css';
import '../../css/f/fd7_frbmd.css';
import '../../css/q/qv_d-ebdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ql8wzqa2k"/><path class="fd7_frbmd"/><path class="qv_d-ebdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-vertical-spacing-line-duotone" /></template>
