<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bspnmyb4c.css';
import '../../css/m/m_1-mhw8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<g class="bi12bsetm"><path class="bspnmyb4c"/><path class="m_1-mhw8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:kette" /></template>
