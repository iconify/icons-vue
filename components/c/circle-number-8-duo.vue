<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkb8-1b0p.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/a/a6e-3_biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkb8-1b0p secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="a6e-3_biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-number-8-duo" /></template>
