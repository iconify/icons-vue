<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n9zc5cbms.css';
import '../../css/r/r4hbm720t.css';
import '../../css/a/anypatboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="n9zc5cbms"/><path clip-rule="evenodd" class="r4hbm720t"/><path clip-rule="evenodd" class="anypatboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:letter-print" /></template>
