<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh5bazbdh.css';
import '../../css/t/t_f65iten.css';
import '../../css/f/faheoc_mo.css';
import '../../css/d/dw8g4-vla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="uh5bazbdh"/><circle class="t_f65iten"/><path class="faheoc_mo"/><path class="dw8g4-vla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:content-delivery-network" /></template>
