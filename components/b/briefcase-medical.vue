<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gyff0-91k.css';
import '../../css/a/a4sazmbph.css';
import '../../css/z/zsgksfvhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="gyff0-91k"/><rect class="a4sazmbph"/><path clip-rule="evenodd" class="zsgksfvhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:briefcase-medical" /></template>
