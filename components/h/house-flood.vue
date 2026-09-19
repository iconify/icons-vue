<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/u/ubyftdn1r.css';
import '../../css/f/fr7u0ubhf.css';
import '../../css/d/d6woa2e3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ubyftdn1r"/><path class="fr7u0ubhf"/><path class="d6woa2e3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-flood" /></template>
