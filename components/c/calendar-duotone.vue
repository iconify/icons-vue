<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lontg97es.css';
import '../../css/b/b5yp74bds.css';
import '../../css/v/v3ztjgbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lontg97es"/><path class="b5yp74bds"/><path class="v3ztjgbwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:calendar-duotone" /></template>
