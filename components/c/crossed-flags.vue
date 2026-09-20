<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znrpuji4k.css';
import '../../css/m/mwzyskgks.css';
import '../../css/f/fp2ytl5nf.css';
import '../../css/h/hv77mauqn.css';
import '../../css/u/udd3bbc2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="znrpuji4k"/><circle class="mwzyskgks"/><circle class="fp2ytl5nf"/><path class="hv77mauqn"/><g class="udd3bbc2x"><circle class="mwzyskgks"/><circle class="fp2ytl5nf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:crossed-flags" /></template>
