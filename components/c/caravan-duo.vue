<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq_x2db-v.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nvnxxlsue.css';
import '../../css/d/d7dea4fys.css';
import '../../css/m/mszde04rh.css';
import '../../css/e/ew6gvneji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq_x2db-v secondary"/><g class="dt0cm9dhy primary"><path class="nvnxxlsue"/><path class="d7dea4fys"/><path class="mszde04rh"/><path class="ew6gvneji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:caravan-duo" /></template>
