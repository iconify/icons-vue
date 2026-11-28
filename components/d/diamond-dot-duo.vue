<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsrgbbb5d.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qyvn42bbq.css';
import '../../css/l/lavl0lbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsrgbbb5d secondary"/><g class="dt0cm9dhy primary"><path class="qyvn42bbq"/><path class="lavl0lbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:diamond-dot-duo" /></template>
