<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/zr3aj01_m.css';
import '../../css/d/d2bzl5g0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="zr3aj01_m"/><path class="d2bzl5g0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bring-to-front-one" /></template>
