<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/f/f7wbymi_z.css';
import '../../css/j/jyta25btr.css';
import '../../css/p/pf42nndkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="f7wbymi_z"/><path class="jyta25btr"/><path class="pf42nndkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:filing-cabinet" /></template>
