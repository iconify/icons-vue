<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/u0r4_lj8o.css';
import '../../css/i/its440yfc.css';
import '../../css/u/ujgww1per.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="u0r4_lj8o"/><path class="its440yfc"/><path class="ujgww1per"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:loader-line-duotone" /></template>
