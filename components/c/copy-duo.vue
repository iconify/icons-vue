<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i24p_w3hn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ib4ikg6hx.css';
import '../../css/e/ekk1d4bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i24p_w3hn secondary"/><g class="dt0cm9dhy primary"><path class="ib4ikg6hx"/><path class="ekk1d4bph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:copy-duo" /></template>
