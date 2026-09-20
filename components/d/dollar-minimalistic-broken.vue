<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gwtb9fb5e.css';
import '../../css/p/p3a3-wxlk.css';
import '../../css/p/p9ekrnbem.css';
import '../../css/k/ko6o-6b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gwtb9fb5e"/><path class="p3a3-wxlk"/><path class="p9ekrnbem"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dollar-minimalistic-broken" /></template>
