<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btnve5bgb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mlhogcckt.css';
import '../../css/c/cj058b15h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btnve5bgb secondary"/><g class="dt0cm9dhy primary"><path class="mlhogcckt"/><path class="cj058b15h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:at-sign-duo" /></template>
