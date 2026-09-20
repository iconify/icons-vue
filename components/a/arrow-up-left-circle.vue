<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l3i8q-r3k.css';
import '../../css/d/dwlwfdcfr.css';
import '../../css/n/n5pc76bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l3i8q-r3k"/><path class="dwlwfdcfr"/><path class="n5pc76bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-up-left-circle" /></template>
