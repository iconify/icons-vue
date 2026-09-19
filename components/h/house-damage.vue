<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/ksso_xfmr.css';
import '../../css/q/qysl9rb8l.css';
import '../../css/b/bel2kzo2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ksso_xfmr"/><path class="qysl9rb8l"/><path class="bel2kzo2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-damage" /></template>
