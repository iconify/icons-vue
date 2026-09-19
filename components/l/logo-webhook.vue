<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pjxpa7bda.css';
import '../../css/h/hb0tznocp.css';
import '../../css/i/inubnybbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pjxpa7bda"/><path class="hb0tznocp"/><path class="inubnybbc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-webhook" /></template>
