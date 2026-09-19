<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/u/uhtqi2bld.css';
import '../../css/z/zfck3lhqy.css';
import '../../css/y/yedi71t4u.css';
import '../../css/o/ovtvrgkrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="uhtqi2bld"/><circle class="zfck3lhqy"/><circle class="yedi71t4u"/><path class="ovtvrgkrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:every-user" /></template>
