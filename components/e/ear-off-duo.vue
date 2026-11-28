<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g11d8ebst.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jwgngrfit.css';
import '../../css/k/kz2jgdb-f.css';
import '../../css/o/ohpg7ib8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g11d8ebst secondary"/><g class="dt0cm9dhy primary"><path class="jwgngrfit"/><path class="kz2jgdb-f"/><path class="ohpg7ib8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ear-off-duo" /></template>
