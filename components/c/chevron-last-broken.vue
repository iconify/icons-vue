<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i4bbelqdd.css';
import '../../css/u/udsce1b5r.css';
import '../../css/n/nqop7gbey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i4bbelqdd"/><path class="udsce1b5r"/><path class="nqop7gbey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevron-last-broken" /></template>
