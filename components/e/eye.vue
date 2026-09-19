<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/u/uxwj_xb5y.css';
import '../../css/z/zs13s_bpz.css';
import '../../css/x/xb15pwbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><circle class="uxwj_xb5y"/><circle class="zs13s_bpz"/><path class="xb15pwbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:eye" /></template>
