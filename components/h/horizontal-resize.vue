<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n-la1r_pz.css';
import '../../css/k/k7bf7us5u.css';
import '../../css/l/l7tubublb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n-la1r_pz"/><path class="k7bf7us5u"/><path class="l7tubublb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:horizontal-resize" /></template>
