<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/suh2x8f3r.css';
import '../../css/t/t4j797bro.css';
import '../../css/x/xqwcnob-h.css';
import '../../css/p/pusf2ucdm.css';
import '../../css/b/brpeugpnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="suh2x8f3r"/><path clip-rule="evenodd" class="t4j797bro"/><path clip-rule="evenodd" class="xqwcnob-h"/><path clip-rule="evenodd" class="pusf2ucdm"/><path class="brpeugpnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:ad" /></template>
