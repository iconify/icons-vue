<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j1zl5-bua.css';
import '../../css/g/gn83_cb7i.css';
import '../../css/j/j1_apjast.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j1zl5-bua"/><path class="gn83_cb7i wm-a"/><path class="j1_apjast"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:air-vent-duo" /></template>
