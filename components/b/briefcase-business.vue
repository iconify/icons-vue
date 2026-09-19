<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o8gm9zlaa.css';
import '../../css/i/iss23tpjy.css';
import '../../css/k/ki55z6ilg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o8gm9zlaa"/><path class="iss23tpjy"/><path class="ki55z6ilg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-business" /></template>
