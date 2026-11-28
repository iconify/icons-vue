<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mk3-rt67g.css';
import '../../css/p/p7kjmnotq.css';
import '../../css/d/dtpklfbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mk3-rt67g"/><path class="p7kjmnotq"/><path class="dtpklfbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-restart" /></template>
