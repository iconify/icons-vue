<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m-ey7ab0y.css';
import '../../css/m/md286fbip.css';
import '../../css/y/ynomorbhb.css';
import '../../css/u/ukh3-twpb.css';
import '../../css/k/k2h3dnbax.css';
import '../../css/u/uf8_11vlk.css';
import '../../css/l/lwa05ovcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="m-ey7ab0y"/><g class="md286fbip"><path class="ynomorbhb"/><path class="ukh3-twpb"/><path class="k2h3dnbax"/><path class="uf8_11vlk"/><path class="lwa05ovcb"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:2give" /></template>
