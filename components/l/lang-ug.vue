<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/i/ik86qab2v.css';
import '../../css/p/pn3yjm3gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="ik86qab2v"/><path class="pn3yjm3gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:lang-ug" /></template>
