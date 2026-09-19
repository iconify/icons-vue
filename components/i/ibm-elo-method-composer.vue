<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvtb7tb3p.css';
import '../../css/g/gor6sh79f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cvtb7tb3p"/><path class="gor6sh79f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-elo-method-composer" /></template>
