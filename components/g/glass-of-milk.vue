<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3824eb3w.css';
import '../../css/u/u5_58bctg.css';
import '../../css/k/kpmaaubsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="l3824eb3w"/><path class="u5_58bctg"/><path class="kpmaaubsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:glass-of-milk" /></template>
