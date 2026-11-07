<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gb8mb3rpq.css';
import '../../css/t/te37o_dxs.css';
import '../../css/r/ribhzvbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gb8mb3rpq"/><path class="te37o_dxs"/><path class="ribhzvbcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-out-line-duotone" /></template>
