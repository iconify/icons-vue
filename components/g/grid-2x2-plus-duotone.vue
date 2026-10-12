<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sp-zmb43i.css';
import '../../css/i/iw329sbdq.css';
import '../../css/d/da6eg2b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sp-zmb43i"/><path class="iw329sbdq"/><path class="da6eg2b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:grid-2x2-plus-duotone" /></template>
