<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zyg886bxh.css';
import '../../css/u/u6equw4su.css';
import '../../css/e/e68b-ibdw.css';
import '../../css/u/u8xvxoo7n.css';
import '../../css/y/ysjr4s0bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="zyg886bxh"/><path class="u6equw4su"/><path clip-rule="evenodd" class="e68b-ibdw"/><path class="u8xvxoo7n"/><path class="ysjr4s0bv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crop-1-bold" /></template>
