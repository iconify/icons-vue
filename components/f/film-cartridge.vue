<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dvy6mmbjg.css';
import '../../css/g/g0preuo0e.css';
import '../../css/c/c9mv_tbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="dvy6mmbjg"/><path clip-rule="evenodd" class="g0preuo0e"/><path class="c9mv_tbxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:film-cartridge" /></template>
