<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/spqxaywrr.css';
import '../../css/m/mp77goa1w.css';
import '../../css/p/pg6c6hbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="spqxaywrr"/><path class="mp77goa1w wm-a"/><path class="pg6c6hbqu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:leaf-duo" /></template>
