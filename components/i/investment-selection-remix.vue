<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhyy4-bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fhyy4-bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:investment-selection-remix" /></template>
