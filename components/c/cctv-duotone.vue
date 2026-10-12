<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x1xr7rb5z.css';
import '../../css/p/pf7_iv0-v.css';
import '../../css/c/c4tkszbbr.css';
import '../../css/a/a_bj4ybzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x1xr7rb5z"/><path class="pf7_iv0-v"/><path class="c4tkszbbr"/><path class="a_bj4ybzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cctv-duotone" /></template>
