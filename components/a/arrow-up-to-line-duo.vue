<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/urex7lgqu.css';
import '../../css/c/cad4hcf2h.css';
import '../../css/f/fwvwu22pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="urex7lgqu"/><path class="cad4hcf2h"/><path class="fwvwu22pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-to-line-duo" /></template>
