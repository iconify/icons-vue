<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h5_h89bsj.css';
import '../../css/n/nef116t2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle transform="matrix(-1 0 0 1 16.654 6.034)" class="h5_h89bsj"/><circle transform="matrix(-1 0 0 1 12.156 5.221)" class="h5_h89bsj"/><circle transform="matrix(-1 0 0 1 8.654 7.94)" class="h5_h89bsj"/><circle transform="matrix(-1 0 0 1 7.685 12.156)" class="h5_h89bsj"/><circle transform="matrix(-1 0 0 1 9.904 15.948)" class="h5_h89bsj"/><path class="nef116t2d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:color-palette" /></template>
