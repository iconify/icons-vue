<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/i11jghbrq.css';
import '../../css/y/yngtobcdp.css';
import '../../css/w/wmhvecc2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i11jghbrq"/><path class="yngtobcdp"/><path class="wmhvecc2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:consumable" /></template>
