<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/u/uolcnlt1k.css';
import '../../css/g/gou96pycw.css';
import '../../css/x/xv28_v7yy.css';
import '../../css/w/wp_uj4b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="uolcnlt1k"/><path class="gou96pycw"/><path class="xv28_v7yy"/><path class="wp_uj4b0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:car-tilt-outline" /></template>
