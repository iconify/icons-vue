<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wks9rvbdz.css';
import '../../css/w/w1piddb9w.css';
import '../../css/n/nclc4jhsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wks9rvbdz"/><path class="w1piddb9w"/><path class="nclc4jhsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:campfire" /></template>
