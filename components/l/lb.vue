<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/k/ksy1gcbdc.css';
import '../../css/u/uzxdcnbti.css';
import '../../css/t/t-dz9qbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="ksy1gcbdc"/><path class="uzxdcnbti"/><path class="t-dz9qbwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:lb" /></template>
