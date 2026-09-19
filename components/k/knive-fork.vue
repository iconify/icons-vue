<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sprkccr_w.css';
import '../../css/o/o5k3y_btt.css';
import '../../css/p/pms32xb-c.css';
import '../../css/g/gywsm-bsw.css';
import '../../css/f/fzpit_b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sprkccr_w"/><path class="o5k3y_btt"/><path class="pms32xb-c"/><path class="gywsm-bsw"/><path class="fzpit_b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:knive-fork" /></template>
