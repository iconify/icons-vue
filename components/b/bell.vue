<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/v1u3x77qg.css';
import '../../css/o/ohr5grb8d.css';
import '../../css/h/hs3xplndx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="v1u3x77qg"/><path class="ohr5grb8d"/><path class="hs3xplndx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:bell" /></template>
