<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/e/e8yohmb3w.css';
import '../../css/m/me1_ckb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="circleFlagsEl0"><circle class="bc1fd0lxe"/></mask><g mask="url(#circleFlagsEl0)"><path class="e8yohmb3w"/><path class="me1_ckb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:el" /></template>
