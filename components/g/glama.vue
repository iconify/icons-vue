<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hm_59sbho.css';
import '../../css/x/x1ct8yiis.css';
import '../../css/x/xcz9gzhia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="hm_59sbho"/><path class="x1ct8yiis"/><path class="xcz9gzhia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:glama" /></template>
