<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xs3pxobcu.css';
import '../../css/e/er5hmdbdf.css';
import '../../css/d/deivui2dq.css';
import '../../css/x/xhkm7y-hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xs3pxobcu"/><path class="er5hmdbdf"/><path class="deivui2dq"/><path class="xhkm7y-hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calculator-broken" /></template>
