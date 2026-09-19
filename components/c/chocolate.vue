<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gnu5dik5b.css';
import '../../css/q/q4rumib0w.css';
import '../../css/v/vp5nx6b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gnu5dik5b"/><path class="q4rumib0w"/><path class="vp5nx6b1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chocolate" /></template>
