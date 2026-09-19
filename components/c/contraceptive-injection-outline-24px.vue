<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g2a9hnbiv.css';
import '../../css/v/vtf5fma1r.css';
import '../../css/u/ulffmnbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g2a9hnbiv"/><path clip-rule="evenodd" class="vtf5fma1r"/><path clip-rule="evenodd" class="ulffmnbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-injection-outline-24px" /></template>
