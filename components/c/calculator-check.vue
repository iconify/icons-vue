<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cezurnb4k.css';
import '../../css/e/e25gc_mcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cezurnb4k"/><path class="e25gc_mcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calculator-check" /></template>
