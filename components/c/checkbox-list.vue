<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hnsc5ccym.css';
import '../../css/d/d1k0wbbmk.css';
import '../../css/t/t4y3w9obw.css';
import '../../css/c/cr9fx3got.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hnsc5ccym"/><rect class="d1k0wbbmk"/><rect class="t4y3w9obw"/><rect class="cr9fx3got"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:checkbox-list" /></template>
