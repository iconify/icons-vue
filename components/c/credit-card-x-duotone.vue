<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r_e3spb3b.css';
import '../../css/j/joz_vvjya.css';
import '../../css/n/n55f-kb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r_e3spb3b"/><path class="joz_vvjya"/><path class="n55f-kb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-x-duotone" /></template>
