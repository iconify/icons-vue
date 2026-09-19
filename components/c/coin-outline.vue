<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dc2wgbcoh.css';
import '../../css/d/dwf9vmmel.css';
import '../../css/o/our-m0bsu.css';
import '../../css/x/xy3osn-xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dc2wgbcoh"/><path class="dwf9vmmel"/><path class="our-m0bsu"/><path class="xy3osn-xf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:coin-outline" /></template>
