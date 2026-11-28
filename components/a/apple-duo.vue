<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khtovtb-c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ltvz_r8sf.css';
import '../../css/p/p1kdwps6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khtovtb-c secondary"/><g class="dt0cm9dhy primary"><path class="ltvz_r8sf"/><path class="p1kdwps6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:apple-duo" /></template>
