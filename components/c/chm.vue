<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/q/q-7r1-bmd.css';
import '../../css/k/kj_hitb4o.css';
import '../../css/s/syrm5jbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsChm0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsChm0)"><path class="q-7r1-bmd"/><path class="kj_hitb4o"/><path class="syrm5jbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:chm" /></template>
