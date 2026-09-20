<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i626vjbuh.css';
import '../../css/e/ecwgwqbhc.css';
import '../../css/h/hrqohn1pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i626vjbuh"/><path class="ecwgwqbhc"/><path class="hrqohn1pc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-broken" /></template>
