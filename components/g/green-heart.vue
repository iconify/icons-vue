<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtemydjmd.css';
import '../../css/t/to-5kdesz.css';
import '../../css/k/kuim36bpx.css';
import '../../css/j/jt3jpeb6n.css';
import '../../css/h/hsixsabso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<mask id="SVGUJ7Mq8OH" width="28" height="25" x="2" y="4" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="dtemydjmd"/></mask><g class="to-5kdesz"><path class="kuim36bpx"/><g mask="url(#SVGUJ7Mq8OH)" class="jt3jpeb6n"><path class="hsixsabso"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:green-heart" /></template>
