<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gqcufpb0p.css';
import '../../css/t/tmkk-ebcz.css';
import '../../css/d/dijsgdc7v.css';
import '../../css/m/mpzv_9bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="gqcufpb0p"/><path class="tmkk-ebcz"/><path class="dijsgdc7v"/><path class="mpzv_9bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrow-solid-curve" /></template>
