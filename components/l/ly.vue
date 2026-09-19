<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q2fcctxvx.css';
import '../../css/o/oiytrebzc.css';
import '../../css/z/z1srs-9rs.css';
import '../../css/i/irkglzlhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q2fcctxvx"/><path class="oiytrebzc"/><path class="z1srs-9rs"/><path class="irkglzlhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ly" /></template>
