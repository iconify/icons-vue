<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lnsnpcbvi.css';
import '../../css/a/aq6xpmbtf.css';
import '../../css/s/stp3nf4wl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lnsnpcbvi"/><path class="aq6xpmbtf"/><path class="stp3nf4wl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:line-dashed-duo" /></template>
