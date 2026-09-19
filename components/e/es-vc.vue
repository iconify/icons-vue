<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/r/r4uaaccdm.css';
import '../../css/i/i-pixzbei.css';
import '../../css/b/brtenrbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="r4uaaccdm"/><path class="i-pixzbei"/><path class="brtenrbvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:es-vc" /></template>
