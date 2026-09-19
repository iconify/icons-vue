<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dpeakr04t.css';
import '../../css/z/zdr2so73c.css';
import '../../css/p/pi0obnw5p.css';
import '../../css/z/zf_qj8moa.css';
import '../../css/s/s0xfuz19y.css';
import '../../css/c/chzoiac_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dpeakr04t"/><path class="zdr2so73c"/><path class="pi0obnw5p"/><path class="zf_qj8moa"/><path class="s0xfuz19y"/><path class="chzoiac_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:icons" /></template>
