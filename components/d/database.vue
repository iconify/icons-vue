<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/f/f4q24bcue.css';
import '../../css/p/ped8-delv.css';
import '../../css/v/v-k6d2bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><ellipse class="f4q24bcue"/><path class="ped8-delv"/><path class="v-k6d2bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:database" /></template>
