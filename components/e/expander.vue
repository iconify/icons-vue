<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pllftbc0b.css';
import '../../css/u/u5sm2-17w.css';
import '../../css/d/dtewxowdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pllftbc0b"/><path class="u5sm2-17w"/><path class="dtewxowdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:expander" /></template>
