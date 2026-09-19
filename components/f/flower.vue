<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufie9ebgy.css';
import '../../css/i/idkm_n_ig.css';
import '../../css/v/vnf09r-ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ufie9ebgy"><path class="idkm_n_ig"/><path class="vnf09r-ls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:flower" /></template>
