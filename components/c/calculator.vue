<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkaz_ncxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="tkaz_ncxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:calculator" /></template>
