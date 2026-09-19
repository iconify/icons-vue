<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk2uwtblc.css';
import '../../css/n/nrjc2qb-u.css';
import '../../css/c/cq0hx26ww.css';
import '../../css/w/wo0ynd7fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vk2uwtblc"/><path class="nrjc2qb-u"/><path class="cq0hx26ww"/><path class="wo0ynd7fl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-west-duo" /></template>
