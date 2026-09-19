<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/j/jrpkb3kfl.css';
import '../../css/y/yitj2s91n.css';
import '../../css/o/ohvbfvvzq.css';
import '../../css/l/lg8zct3ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="jrpkb3kfl"/><path class="yitj2s91n"/><path class="ohvbfvvzq"/><path class="lg8zct3ui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-3-outline" /></template>
