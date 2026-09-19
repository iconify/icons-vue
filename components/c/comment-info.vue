<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a0bj6zbkt.css';
import '../../css/k/k82jeybsw.css';
import '../../css/v/vl360nb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="a0bj6zbkt"/><path class="k82jeybsw"/><path class="vl360nb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-info" /></template>
