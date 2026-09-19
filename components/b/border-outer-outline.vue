<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7mn_xgnv.css';
import '../../css/o/oojk4pbmj.css';
import '../../css/y/ytntd_8jh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="oojk4pbmj"/><path class="ytntd_8jh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:border-outer-outline" /></template>
