<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n3r3aob5w.css';
import '../../css/j/jg1pj_v2g.css';
import '../../css/p/pfodkzbrw.css';
import '../../css/d/dg5kmnbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n3r3aob5w"/><path class="jg1pj_v2g wm-shadow"/><path class="pfodkzbrw"/><path class="dg5kmnbiz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:fireplace-engrave" /></template>
