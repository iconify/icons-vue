<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/ck-crre5h.css';
import '../../css/o/oy1zyc70h.css';
import '../../css/s/sflfg-b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ck-crre5h"/><path class="oy1zyc70h"/><path class="sflfg-b2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-bottom-line-duotone" /></template>
