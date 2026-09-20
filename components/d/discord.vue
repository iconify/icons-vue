<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgy2bfb1z.css';
import '../../css/u/uyj_e1b4g.css';
import '../../css/d/dw4u2gb_w.css';
import '../../css/u/u33y14bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path clip-rule="evenodd" class="qgy2bfb1z"/><path clip-rule="evenodd" class="uyj_e1b4g"/><path class="dw4u2gb_w"/><path class="u33y14bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:discord" /></template>
