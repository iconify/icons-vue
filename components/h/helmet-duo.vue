<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01xbfbgf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d-9bk_b_m.css';
import '../../css/w/wf2t-zq0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h01xbfbgf secondary"/><g class="dt0cm9dhy primary"><path class="d-9bk_b_m"/><path class="wf2t-zq0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:helmet-duo" /></template>
