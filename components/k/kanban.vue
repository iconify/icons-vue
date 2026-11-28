<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uacp7pu3u.css';
import '../../css/d/db-0dmlok.css';
import '../../css/x/x7vrpjlro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uacp7pu3u"/><path class="db-0dmlok"/><path class="x7vrpjlro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:kanban" /></template>
