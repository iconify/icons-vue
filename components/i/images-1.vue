<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/mf4oncbfb.css';
import '../../css/a/almr0fnyn.css';
import '../../css/y/y8y_uhilr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="mf4oncbfb"/><path class="almr0fnyn"/><path class="y8y_uhilr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:images-1" /></template>
