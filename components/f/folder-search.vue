<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flen3tbdj.css';
import '../../css/u/u_osh_p5x.css';
import '../../css/p/pm27xrbad.css';
import '../../css/r/r0cxtj73q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><path class="u_osh_p5x"/><circle class="pm27xrbad"/><path class="r0cxtj73q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-search" /></template>
