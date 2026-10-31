<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f70r1k1nq.css';
import '../../css/b/bn3ushtud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="f70r1k1nq"/><path class="bn3ushtud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:cn" /></template>
