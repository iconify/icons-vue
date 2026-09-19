<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/ryh33yj2x.css';
import '../../css/a/au4fvpqfr.css';
import '../../css/x/xqsd73i5h.css';
import '../../css/h/hxbz7cbuk.css';
import '../../css/v/vuvnirmvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(1 3)" class="bi12bsetm"><path class="ryh33yj2x"/><path class="au4fvpqfr"/><path class="xqsd73i5h"/><ellipse class="hxbz7cbuk"/><ellipse class="vuvnirmvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:casette" /></template>
