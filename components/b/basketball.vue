<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-c8a2bra.css';
import '../../css/z/zbfz6_e-q.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/y/y1j8wi2gc.css';
import '../../css/c/cz-zmg-cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="z-c8a2bra"/><path class="zbfz6_e-q"/><g class="ij2x_72vy"><path class="y1j8wi2gc"/><circle class="cz-zmg-cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:basketball" /></template>
