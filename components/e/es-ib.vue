<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/b/bl_52xb0t.css';
import '../../css/n/np5rx5hvg.css';
import '../../css/l/lt1n64b6s.css';
import '../../css/u/u6wj_zbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="bl_52xb0t"/><path class="np5rx5hvg"/><path class="lt1n64b6s"/><path class="u6wj_zbic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:es-ib" /></template>
