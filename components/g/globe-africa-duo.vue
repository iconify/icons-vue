<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ij883nb6j.css';
import '../../css/n/ninqfyb4i.css';
import '../../css/w/wkizchjmy.css';
import '../../css/r/rau80ob0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ij883nb6j"/><path clip-rule="evenodd" class="ninqfyb4i"/><path class="wkizchjmy"/><path class="rau80ob0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-africa-duo" /></template>
