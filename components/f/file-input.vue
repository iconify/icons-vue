<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/d_4ikg2gj.css';
import '../../css/z/zp-stnbon.css';
import '../../css/k/k4g8l4bne.css';
import '../../css/s/sgzl7tb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="d_4ikg2gj wm-shadow"/><path class="wm-shadow zp-stnbon"/><path class="k4g8l4bne"/><path class="sgzl7tb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:file-input" /></template>
