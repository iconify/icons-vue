<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rmku--bxg.css';
import '../../css/e/em_i-2_kp.css';
import '../../css/u/unv51cu4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rmku--bxg wm-shadow"/><path class="em_i-2_kp wm-shadow"/><path class="unv51cu4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:bamboo" /></template>
