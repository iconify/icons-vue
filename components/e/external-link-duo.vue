<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s0s9ztoap.css';
import '../../css/h/h7btge1_e.css';
import '../../css/v/vanl12bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s0s9ztoap"/><path class="h7btge1_e wm-a"/><path class="vanl12bnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:external-link-duo" /></template>
