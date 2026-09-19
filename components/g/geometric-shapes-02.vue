<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pz3scgbdp.css';
import '../../css/v/vy_h11b1c.css';
import '../../css/r/rwivxdqcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="pz3scgbdp"/><path class="vy_h11b1c"/><path class="rwivxdqcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:geometric-shapes-02" /></template>
