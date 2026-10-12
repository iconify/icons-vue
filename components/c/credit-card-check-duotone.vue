<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wxmimtf1y.css';
import '../../css/j/joz_vvjya.css';
import '../../css/y/ykb_6ib2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wxmimtf1y"/><path class="joz_vvjya"/><path class="ykb_6ib2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:credit-card-check-duotone" /></template>
