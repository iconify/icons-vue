<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w-1c8gqjv.css';
import '../../css/w/wnskr0b-c.css';
import '../../css/n/n4gnk9blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w-1c8gqjv"/><path class="wnskr0b-c"/><path class="n4gnk9blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bed-single-01" /></template>
