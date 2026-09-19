<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/f/fxtjowbmc.css';
import '../../css/a/a9a5abcwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><rect transform="rotate(45 40 12)" class="fxtjowbmc"/><rect transform="rotate(45 40 26)" class="a9a5abcwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:diamond-1" /></template>
