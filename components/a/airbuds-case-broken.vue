<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/ka16ahzxe.css';
import '../../css/m/mgi3zn3tq.css';
import '../../css/u/u296q5x9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ka16ahzxe"/><path class="mgi3zn3tq"/><path class="u296q5x9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-case-broken" /></template>
