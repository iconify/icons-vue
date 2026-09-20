<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cej47kqnc.css';
import '../../css/r/rdfge7bju.css';
import '../../css/c/cln8p0noc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cej47kqnc"/><path class="rdfge7bju"/><path class="cln8p0noc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:document-popular" /></template>
