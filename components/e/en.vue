<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/b/bgsd25l1y.css';
import '../../css/z/zdklvc37u.css';
import '../../css/d/drmk0woyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsEn0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsEn0)"><path class="bgsd25l1y"/><path class="zdklvc37u"/><path class="drmk0woyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:en" /></template>
