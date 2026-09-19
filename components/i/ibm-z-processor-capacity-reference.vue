<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8dna0b9r.css';
import '../../css/h/hgwl5bclr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l8dna0b9r"/><path class="hgwl5bclr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-processor-capacity-reference" /></template>
