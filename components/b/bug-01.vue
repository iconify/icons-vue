<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mkwo76bgt.css';
import '../../css/t/t4r4iccxi.css';
import '../../css/k/kgm_pmmhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mkwo76bgt"/><path class="t4r4iccxi"/><path class="kgm_pmmhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bug-01" /></template>
