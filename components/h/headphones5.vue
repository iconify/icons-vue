<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/x/xle_1ccvl.css';
import '../../css/m/ma20n0b8n.css';
import '../../css/r/rb4241btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="xle_1ccvl"/><path class="ma20n0b8n"/><path class="rb4241btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones5" /></template>
