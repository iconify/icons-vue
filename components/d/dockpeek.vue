<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvr4ljncy.css';
import '../../css/q/qf_fqfblh.css';
import '../../css/s/sopu2lbmd.css';
import '../../css/r/rksq5bbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="uvr4ljncy"/><path class="qf_fqfblh"/><path class="sopu2lbmd"/><circle class="rksq5bbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dockpeek" /></template>
