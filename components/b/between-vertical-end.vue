<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/c3veszb2o.css';
import '../../css/j/jf5s6ugur.css';
import '../../css/d/dwec3ac1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="c3veszb2o"/><path class="jf5s6ugur"/><rect class="dwec3ac1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:between-vertical-end" /></template>
