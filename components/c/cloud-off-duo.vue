<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkgs06hvj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i3frhyb2m.css';
import '../../css/c/c3c_ciakh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkgs06hvj secondary"/><g class="dt0cm9dhy primary"><path class="i3frhyb2m"/><path class="c3c_ciakh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-off-duo" /></template>
