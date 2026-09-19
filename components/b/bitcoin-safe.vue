<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/go5qx8a4v.css';
import '../../css/z/zbuz9ebso.css';
import '../../css/g/gu9f0qb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="go5qx8a4v"/><path class="zbuz9ebso"/><path class="gu9f0qb-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bitcoin-safe" /></template>
