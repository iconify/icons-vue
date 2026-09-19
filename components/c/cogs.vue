<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/o-9h659ll.css';
import '../../css/m/mlwa6977n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":84,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="o-9h659ll"/><path class="mlwa6977n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:cogs" /></template>
