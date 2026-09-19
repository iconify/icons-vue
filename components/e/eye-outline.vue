<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7mn_xgnv.css';
import '../../css/q/qcums4bin.css';
import '../../css/u/u0h4nqdfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="qcums4bin"/><path class="u0h4nqdfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-outline" /></template>
