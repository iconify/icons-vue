<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c8yuot4zz.css';
import '../../css/d/duo8u5b0b.css';
import '../../css/s/sukz5in0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c8yuot4zz"/><path class="duo8u5b0b"/><path class="sukz5in0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-add-line-duotone" /></template>
