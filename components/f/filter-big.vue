<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/o/o_eemtw3s.css';
import '../../css/m/mzyopqbdv.css';
import '../../css/y/yhxdwobwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="o_eemtw3s"/><circle transform="rotate(90 7 8)" class="mzyopqbdv"/><circle transform="rotate(90 17 16)" class="yhxdwobwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:filter-big" /></template>
