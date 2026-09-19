<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/b/bt6y-5bmv.css';
import '../../css/k/kid_vm7-j.css';
import '../../css/y/yi-i_vb8s.css';
import '../../css/w/wnbbxc35x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="kb9zbkb1z"/><path class="bt6y-5bmv"/><circle class="kid_vm7-j"/><path class="yi-i_vb8s"/><path class="wnbbxc35x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:death-star" /></template>
