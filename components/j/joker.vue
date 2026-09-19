<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yom9-8bmz.css';
import '../../css/o/occmn0cmv.css';
import '../../css/n/nut2xvvam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="yom9-8bmz"/><path class="occmn0cmv"/><path class="nut2xvvam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:joker" /></template>
