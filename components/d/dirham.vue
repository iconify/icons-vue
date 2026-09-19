<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/drbzacc-b.css';
import '../../css/h/hkrz-8b6k.css';
import '../../css/e/e_xtotenz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="drbzacc-b"/><path class="hkrz-8b6k"/><path class="e_xtotenz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:dirham" /></template>
