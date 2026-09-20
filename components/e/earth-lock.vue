<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cz1j5_vyb.css';
import '../../css/g/gbw7dvbeh.css';
import '../../css/d/dydq24bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cz1j5_vyb"/><path class="gbw7dvbeh"/><rect class="dydq24bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:earth-lock" /></template>
