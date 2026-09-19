<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nffuxgb0d.css';
import '../../css/i/idjsc19lu.css';
import '../../css/j/jgg0-yb6i.css';
import '../../css/j/jz2ddmbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nffuxgb0d"/><path class="idjsc19lu"/><path class="jgg0-yb6i"/><path class="jz2ddmbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bed-outline" /></template>
