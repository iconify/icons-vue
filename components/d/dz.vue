<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/s/shrwr-09x.css';
import '../../css/p/p1a8k8bml.css';
import '../../css/r/rztdzfbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="shrwr-09x"/><path class="p1a8k8bml"/><path class="rztdzfbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:dz" /></template>
