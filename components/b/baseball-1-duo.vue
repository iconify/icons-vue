<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/eum8pabgr.css';
import '../../css/t/tuua3db3n.css';
import '../../css/g/gng0j2b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="eum8pabgr"/><path class="tuua3db3n"/><path class="gng0j2b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:baseball-1-duo" /></template>
