<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/b/bgkze4e7q.css';
import '../../css/k/kn_2t0bjv.css';
import '../../css/k/ktgvdwb7j.css';
import '../../css/x/xusl85bge.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZ2KWNSfL"><g class="gopnm44um"><path class="bgkze4e7q"/><path class="kn_2t0bjv"/><path class="ktgvdwb7j"/><path class="xusl85bge"/></g></mask></defs><path mask="url(#SVGZ2KWNSfL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bottle-two" /></template>
