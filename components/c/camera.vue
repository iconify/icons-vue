<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1dr-lz2y.css';
import '../../css/d/dccl6cslv.css';
import '../../css/b/bz199wbrk.css';
import '../../css/j/jrvk_k-kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="g1dr-lz2y"/><path class="dccl6cslv"/><circle class="bz199wbrk"/><path class="jrvk_k-kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:camera" /></template>
