<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zcxbg4bau.css';
import '../../css/g/grq3s_b1n.css';
import '../../css/y/y79as4lbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zcxbg4bau"/><path class="grq3s_b1n"/><path class="y79as4lbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-0-duo" /></template>
