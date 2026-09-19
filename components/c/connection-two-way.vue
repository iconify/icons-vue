<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7-5t4bnl.css';
import '../../css/h/hgamat_lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q7-5t4bnl"/><path class="hgamat_lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connection-two-way" /></template>
