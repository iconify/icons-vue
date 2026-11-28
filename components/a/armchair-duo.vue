<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9sk95bmy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jwtrj3ybq.css';
import '../../css/p/ppn14wb1e.css';
import '../../css/d/debbmob7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9sk95bmy secondary"/><g class="dt0cm9dhy primary"><path class="jwtrj3ybq"/><path class="ppn14wb1e"/><path class="debbmob7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:armchair-duo" /></template>
