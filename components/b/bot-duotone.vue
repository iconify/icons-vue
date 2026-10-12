<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u352vjp6z.css';
import '../../css/p/p_e-hdc_r.css';
import '../../css/r/r099n9bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u352vjp6z"/><path class="p_e-hdc_r"/><path class="r099n9bbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-duotone" /></template>
