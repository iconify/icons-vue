<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/cvcvhiugj.css';
import '../../css/o/otj-prbjf.css';
import '../../css/k/k2hr7pzpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="cvcvhiugj"/><path class="otj-prbjf"/><path class="k2hr7pzpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:coin" /></template>
