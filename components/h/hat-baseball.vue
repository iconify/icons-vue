<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cc-mb1skd.css';
import '../../css/i/i_z5bmbxi.css';
import '../../css/b/b_garkb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cc-mb1skd"/><path class="i_z5bmbxi"/><path class="b_garkb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:hat-baseball" /></template>
