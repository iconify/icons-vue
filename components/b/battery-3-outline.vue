<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b_zop_bkd.css';
import '../../css/k/k1u3rdh2l.css';
import '../../css/t/t018kgb2u.css';
import '../../css/w/wa93a239p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="b_zop_bkd"/><path class="k1u3rdh2l"/><path class="t018kgb2u"/><path class="wa93a239p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-3-outline" /></template>
