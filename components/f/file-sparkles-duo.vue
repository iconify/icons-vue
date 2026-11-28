<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub0_xdb6u.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kfp3c8bsz.css';
import '../../css/c/ct5w8kbba.css';
import '../../css/t/tkrpcdone.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary ub0_xdb6u"/><g class="dt0cm9dhy primary"><path class="kfp3c8bsz"/><path class="ct5w8kbba"/><path class="tkrpcdone"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-sparkles-duo" /></template>
