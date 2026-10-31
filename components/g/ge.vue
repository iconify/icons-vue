<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d2gqvvb6k.css';
import '../../css/w/w1a_s9bsr.css';
import '../../css/r/rne3g0oqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":200};
const content = `<g class="ft5dv1b6b"><path class="d2gqvvb6k"/><path class="w1a_s9bsr"/><path class="rne3g0oqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ge" /></template>
