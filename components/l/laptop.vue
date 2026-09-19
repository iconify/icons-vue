<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/ft8lohb2t.css';
import '../../css/g/gwjg53brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="ft8lohb2t"/><path class="gwjg53brw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:laptop" /></template>
