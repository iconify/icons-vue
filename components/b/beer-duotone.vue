<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wmz342byi.css';
import '../../css/v/vswt5ex9h.css';
import '../../css/j/j7mlzqbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wmz342byi"/><path class="vswt5ex9h"/><path class="j7mlzqbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:beer-duotone" /></template>
