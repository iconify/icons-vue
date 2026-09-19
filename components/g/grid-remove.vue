<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/h/h6axb1buv.css';
import '../../css/n/nljoyacmt.css';
import '../../css/w/wop--n-hn.css';
import '../../css/k/k75pw74wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="gopnm44um"><rect class="h6axb1buv"/><rect class="nljoyacmt"/><rect class="wop--n-hn"/><path class="k75pw74wa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:grid-remove" /></template>
