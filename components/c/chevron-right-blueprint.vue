<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/tnsdjoz2v.css';
import '../../css/y/y1yeo1vat.css';
import '../../css/a/a2qsicn0m.css';
import '../../css/p/pw12eebpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="tnsdjoz2v wm-deco"/><path class="wm-deco y1yeo1vat"/><path class="a2qsicn0m"/><path class="pw12eebpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-right-blueprint" /></template>
