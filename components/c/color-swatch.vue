<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/idfvmxr2o.css';
import '../../css/u/uc13pobzv.css';
import '../../css/x/x3sbhjonu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="idfvmxr2o"/><path class="uc13pobzv"/><path class="x3sbhjonu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:color-swatch" /></template>
