<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/ds8d-1bsn.css';
import '../../css/m/m3wwuvbrm.css';
import '../../css/l/lyd1vfrtt.css';
import '../../css/l/l2ez41big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ds8d-1bsn"/><path clip-rule="evenodd" class="m3wwuvbrm"/><path clip-rule="evenodd" class="lyd1vfrtt"/><path class="l2ez41big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:car-crash-bold" /></template>
