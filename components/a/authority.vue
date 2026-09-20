<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhe70kwmw.css';
import '../../css/f/f-6nxexvx.css';
import '../../css/w/wwemd7z7m.css';
import '../../css/w/wa4t1cfmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="bhe70kwmw"/><path class="f-6nxexvx"/><path class="wwemd7z7m"/><path class="wa4t1cfmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:authority" /></template>
