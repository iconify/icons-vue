<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-czgsbtt.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/eldr0wm6j.css';
import '../../css/v/vm1xymzfr.css';
import '../../css/q/ql6x9rb7p.css';
import '../../css/x/xamkilm_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-czgsbtt secondary"/><g class="dt0cm9dhy primary"><path class="eldr0wm6j"/><path class="vm1xymzfr"/><path class="ql6x9rb7p"/><path class="xamkilm_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gem-duo" /></template>
