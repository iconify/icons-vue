<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/sybczbbpf.css';
import '../../css/u/uw18y9boo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="sybczbbpf"/><path class="uw18y9boo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:comments-outline" /></template>
