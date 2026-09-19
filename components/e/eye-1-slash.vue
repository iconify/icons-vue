<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kh3iwjkha.css';
import '../../css/r/r5hrfmbxe.css';
import '../../css/n/n6fxwacvj.css';
import '../../css/f/fcbtlcmjz.css';
import '../../css/v/vn8ld76mb.css';
import '../../css/c/cvto2gunb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kh3iwjkha"/><path class="r5hrfmbxe"/><path clip-rule="evenodd" class="n6fxwacvj"/><path class="fcbtlcmjz"/><path class="vn8ld76mb"/><path class="cvto2gunb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:eye-1-slash" /></template>
