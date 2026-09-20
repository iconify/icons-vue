<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2csbibpu.css';
import '../../css/m/mkb8spb3x.css';
import '../../css/w/wyoo44k5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":187.485};
const content = `<g class="g2csbibpu"><path class="mkb8spb3x"/><path class="wyoo44k5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bethesda" /></template>
