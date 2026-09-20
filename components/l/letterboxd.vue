<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e76parb_w.css';
import '../../css/q/qqt6mfb8z.css';
import '../../css/d/dypwk2lxc.css';
import '../../css/r/rkf5-q5qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e76parb_w"/><path class="qqt6mfb8z"/><path class="dypwk2lxc"/><path class="rkf5-q5qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:letterboxd" /></template>
