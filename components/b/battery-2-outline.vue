<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/x4ohvibkb.css';
import '../../css/k/k1u3rdh2l.css';
import '../../css/c/cgfk3wd4h.css';
import '../../css/w/wa93a239p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="x4ohvibkb"/><path class="k1u3rdh2l"/><path class="cgfk3wd4h"/><path class="wa93a239p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-2-outline" /></template>
