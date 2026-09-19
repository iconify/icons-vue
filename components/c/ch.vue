<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t5kc42b7b.css';
import '../../css/a/a_5y6ozvk.css';
import '../../css/f/fxf6_0bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":301};
const content = `<g class="ft5dv1b6b"><path class="t5kc42b7b"/><path class="a_5y6ozvk"/><path class="fxf6_0bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ch" /></template>
