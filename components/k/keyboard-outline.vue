<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p07tmccvv.css';
import '../../css/i/iy87egbjv.css';
import '../../css/f/fv7etkbcn.css';
import '../../css/k/krd-pdbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="p07tmccvv"><path class="iy87egbjv"/><path class="fv7etkbcn"/><path class="krd-pdbsx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:keyboard-outline" /></template>
