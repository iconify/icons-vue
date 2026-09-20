<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/owjk9o9eq.css';
import '../../css/a/a-hn66c-d.css';
import '../../css/x/xohw_uboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="owjk9o9eq"/><path class="a-hn66c-d"/><path class="xohw_uboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:amusement-park-ferris-wheel" /></template>
