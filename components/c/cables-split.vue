<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r4b2gwbvq.css';
import '../../css/p/p3w2d7x_w.css';
import '../../css/g/geahrbbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r4b2gwbvq"/><path class="p3w2d7x_w"/><path class="geahrbbur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cables-split" /></template>
