<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z5pt0aclp.css';
import '../../css/g/g3u0jliin.css';
import '../../css/b/bj1z3ub6e.css';
import '../../css/h/hcbngtbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="z5pt0aclp"/><path class="g3u0jliin"/><path class="bj1z3ub6e"/><path class="hcbngtbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baseball-1-bold" /></template>
