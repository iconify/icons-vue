<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/p3o4dvbqb.css';
import '../../css/y/y2r600b7v.css';
import '../../css/z/zlf7r1kic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p3o4dvbqb"/><rect class="y2r600b7v"/><path class="zlf7r1kic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:copy-slash" /></template>
