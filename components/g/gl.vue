<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/i/i9u83363m.css';
import '../../css/n/nag_kzbmf.css';
import '../../css/y/yhuvbkbie.css';
import '../../css/c/c17uwjbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="i9u83363m"/><path class="nag_kzbmf"/><path class="yhuvbkbie"/><path class="c17uwjbkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:gl" /></template>
