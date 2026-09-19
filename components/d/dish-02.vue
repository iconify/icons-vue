<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mwqjmhb_t.css';
import '../../css/w/wpo6wibuz.css';
import '../../css/c/c9qeufl8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mwqjmhb_t"/><path class="wpo6wibuz"/><path class="c9qeufl8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dish-02" /></template>
