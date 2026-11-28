<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e73euiyzf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rch4b20wr.css';
import '../../css/m/mzvx1_v6v.css';
import '../../css/k/ktnm9mblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e73euiyzf secondary"/><g class="dt0cm9dhy primary"><path class="rch4b20wr"/><path class="mzvx1_v6v"/><path class="ktnm9mblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gauge-alert-duo" /></template>
