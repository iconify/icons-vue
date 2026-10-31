<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/eup7q5r0k.css';
import '../../css/s/swzvg8b8g.css';
import '../../css/m/mf08bkvgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="eup7q5r0k wm-shadow"/><path class="swzvg8b8g wm-shadow"/><path class="mf08bkvgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:circle-dashed" /></template>
