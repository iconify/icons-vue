<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/epg8ibcng.css';
import '../../css/u/uhro_3l0u.css';
import '../../css/i/iu5wbjbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="epg8ibcng"/><path class="uhro_3l0u"/><path class="iu5wbjbno"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-check-solid" /></template>
