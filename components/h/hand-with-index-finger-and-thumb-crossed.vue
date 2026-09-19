<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/myb7yfwem.css';
import '../../css/v/vgystqbcr.css';
import '../../css/l/llh36p0xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="myb7yfwem"/><path class="vgystqbcr"/><path class="llh36p0xj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hand-with-index-finger-and-thumb-crossed" /></template>
