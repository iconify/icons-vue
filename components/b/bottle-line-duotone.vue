<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wf6hfwbfe.css';
import '../../css/r/r7j2fkb1b.css';
import '../../css/d/d9nm02b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wf6hfwbfe"/><path class="r7j2fkb1b"/><path class="d9nm02b3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bottle-line-duotone" /></template>
