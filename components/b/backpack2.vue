<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/osq3ckenx.css';
import '../../css/h/hyystbc4j.css';
import '../../css/e/emip_1b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="osq3ckenx"/><path class="hyystbc4j"/><path class="emip_1b-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:backpack2" /></template>
