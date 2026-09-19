<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kh1v-obsc.css';
import '../../css/z/za5v8ccay.css';
import '../../css/m/myvgrmb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kh1v-obsc"/><path clip-rule="evenodd" class="za5v8ccay"/><path class="myvgrmb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:headphones" /></template>
