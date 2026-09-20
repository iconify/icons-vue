<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o6cb9_bxf.css';
import '../../css/s/siz28rbxw.css';
import '../../css/l/lx85-ac0b.css';
import '../../css/c/c2ccr1cfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o6cb9_bxf"/><path class="siz28rbxw"/><path class="lx85-ac0b"/><path class="c2ccr1cfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-broken" /></template>
