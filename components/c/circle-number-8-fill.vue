<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bue_g-b7r.css';
import '../../css/t/tsenyx-qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="bue_g-b7r"/><path clip-rule="evenodd" class="tsenyx-qb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-8-fill" /></template>
