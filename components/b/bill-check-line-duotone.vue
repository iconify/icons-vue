<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lgo1e5vcg.css';
import '../../css/z/z8b6ep4dx.css';
import '../../css/t/tnf8gbb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lgo1e5vcg"/><path class="z8b6ep4dx"/><path class="tnf8gbb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-check-line-duotone" /></template>
