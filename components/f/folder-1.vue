<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/dkp5t5bjh.css';
import '../../css/h/hepxbzbrb.css';
import '../../css/l/l9tot5bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="dkp5t5bjh"/><path class="hepxbzbrb"/><path class="l9tot5bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:folder-1" /></template>
