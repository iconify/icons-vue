<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k59vwbc7q.css';
import '../../css/o/o4lci2bal.css';
import '../../css/c/c66j5y1jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k59vwbc7q"/><path class="o4lci2bal"/><path class="c66j5y1jh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lamp-ceiling" /></template>
