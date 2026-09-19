<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/t/tad6x19rh.css';
import '../../css/c/cjd6r3oou.css';
import '../../css/i/i-lxrwbzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="tad6x19rh"/><path class="cjd6r3oou"/><path class="i-lxrwbzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:et-am" /></template>
