<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f5mcp3p6l.css';
import '../../css/e/e51nzac3w.css';
import '../../css/k/kqbg0g8jb.css';
import '../../css/k/ko6o-6b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f5mcp3p6l"/><path class="e51nzac3w"/><path class="kqbg0g8jb"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:basketball-broken" /></template>
