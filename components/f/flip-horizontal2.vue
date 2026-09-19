<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/x/xkzigccsu.css';
import '../../css/j/jycvhms3v.css';
import '../../css/f/farndtbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="xkzigccsu"/><path class="jycvhms3v"/><path class="farndtbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flip-horizontal2" /></template>
