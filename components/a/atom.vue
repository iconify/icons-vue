<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jxl67pbry.css';
import '../../css/t/t0kpu6b6r.css';
import '../../css/x/xcwnt1qrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="jxl67pbry"/><path class="t0kpu6b6r"/><path class="xcwnt1qrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:atom" /></template>
