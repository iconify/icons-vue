<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x_dnedc0a.css';
import '../../css/z/zrzqsnbdu.css';
import '../../css/m/m0bfmobtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="x_dnedc0a"/><path class="zrzqsnbdu"/><path class="m0bfmobtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:clock-fast" /></template>
