<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dreuuh66c.css';
import '../../css/c/c7l0uwbsa.css';
import '../../css/d/dfm8uyd9a.css';
import '../../css/k/khrsx4-mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dreuuh66c"/><path class="c7l0uwbsa"/><path class="dfm8uyd9a"/><path class="khrsx4-mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-oceania-outline" /></template>
