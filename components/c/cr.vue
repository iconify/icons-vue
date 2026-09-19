<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/v3at201ox.css';
import '../../css/t/tnp2i7bvy.css';
import '../../css/b/bi6bn9t7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="v3at201ox"/><path class="tnp2i7bvy"/><path class="bi6bn9t7y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:cr" /></template>
