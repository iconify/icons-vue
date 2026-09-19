<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib5j_-bhr.css';
import '../../css/t/t5_nw5bsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ib5j_-bhr"/><path class="t5_nw5bsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:chart-line" /></template>
