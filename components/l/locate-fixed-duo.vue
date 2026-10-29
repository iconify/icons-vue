<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8ue_zwas.css';
import '../../css/h/hbi8hhkfx.css';
import '../../css/v/v9kvji8te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p8ue_zwas"/><path class="hbi8hhkfx wm-a"/><path class="v9kvji8te"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:locate-fixed-duo" /></template>
