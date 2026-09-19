<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb55jl95u.css';
import '../../css/r/rh1pnvbcd.css';
import '../../css/c/c9bteb4uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="sb55jl95u"/><path class="rh1pnvbcd"/><path class="c9bteb4uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-rotary-straight-filled" /></template>
