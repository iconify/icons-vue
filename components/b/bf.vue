<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/r/r8qbw6a5a.css';
import '../../css/g/gw67nib-g.css';
import '../../css/s/s07tpmuyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="r8qbw6a5a"/><path class="gw67nib-g"/><path class="s07tpmuyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:bf" /></template>
