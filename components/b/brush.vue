<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n_gsv3buj.css';
import '../../css/m/mx3kewvpy.css';
import '../../css/h/h_nyhbbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_gsv3buj"/><path class="mx3kewvpy"/><path class="h_nyhbbhu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brush" /></template>
