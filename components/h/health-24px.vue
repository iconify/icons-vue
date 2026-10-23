<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptbfn1blm.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vb3vy8bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGuhAOzcZm" class="ptbfn1blm"/></defs><mask id="SVGfAzgfd8L" class="ft5dv1b6b"><use href="#SVGuhAOzcZm" clip-rule="evenodd" class="d2kvgvbvc"/></mask><g class="cuyn6tgcc"><use href="#SVGuhAOzcZm" clip-rule="evenodd" class="d2kvgvbvc"/><path mask="url(#SVGfAzgfd8L)" class="vb3vy8bot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-24px" /></template>
