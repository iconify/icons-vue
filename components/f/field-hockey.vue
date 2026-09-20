<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5wpiebts.css';
import '../../css/h/hp6kgdb8g.css';
import '../../css/f/fu0mhq30y.css';
import '../../css/b/boy9x7b1i.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/h/hrbf4hbct.css';
import '../../css/j/ju8gylkpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l5wpiebts"/><path class="hp6kgdb8g"/><circle class="fu0mhq30y"/><path class="boy9x7b1i"/><g class="ij2x_72vy"><circle class="hrbf4hbct"/><path class="ju8gylkpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:field-hockey" /></template>
