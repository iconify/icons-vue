<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_09uzbol.css';
import '../../css/r/reipi0w6l.css';
import '../../css/v/vua7q5rtg.css';
import '../../css/q/qtvivvozr.css';
import '../../css/s/suavi9osi.css';
import '../../css/o/o69beaclm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k_09uzbol"/><path class="reipi0w6l"/><path class="vua7q5rtg"/><g class="qtvivvozr"><path class="suavi9osi"/><path class="o69beaclm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:leftwards-pushing-hand" /></template>
