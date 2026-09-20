<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n8zs0qb3h.css';
import '../../css/a/ace-nuvps.css';
import '../../css/r/rvd7q59pv.css';
import '../../css/s/sb7v6-b6z.css';
import '../../css/l/lpln-2bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n8zs0qb3h"/><path class="ace-nuvps"/><path class="rvd7q59pv"/><path class="sb7v6-b6z"/><path class="lpln-2bzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bed-linear" /></template>
