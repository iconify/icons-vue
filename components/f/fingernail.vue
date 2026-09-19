<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nn4_--rny.css';
import '../../css/g/g7qlcfhvp.css';
import '../../css/p/plr7vwr7h.css';
import '../../css/x/x9avr_b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nn4_--rny"/><path class="g7qlcfhvp"/><rect class="plr7vwr7h"/><path class="x9avr_b1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:fingernail" /></template>
