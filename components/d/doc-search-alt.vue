<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/u/u3uh19bmf.css';
import '../../css/l/lkliae68h.css';
import '../../css/y/ysqi2pc_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u3uh19bmf"/><path class="lkliae68h"/><path class="ysqi2pc_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:doc-search-alt" /></template>
