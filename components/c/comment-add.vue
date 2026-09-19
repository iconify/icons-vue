<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c_wdxn8ce.css';
import '../../css/k/k82jeybsw.css';
import '../../css/l/lqoaljmvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="c_wdxn8ce"/><path class="k82jeybsw"/><path class="lqoaljmvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-add" /></template>
