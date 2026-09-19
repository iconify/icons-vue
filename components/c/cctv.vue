<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/a2arncpdg.css';
import '../../css/y/ypq9i8bvk.css';
import '../../css/j/j1d-3tb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="a2arncpdg"/><path class="ypq9i8bvk"/><path class="j1d-3tb9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cctv" /></template>
