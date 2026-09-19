<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/s79qgjdvm.css';
import '../../css/p/p49qakbea.css';
import '../../css/l/lifkejbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="s79qgjdvm"/><path class="p49qakbea"/><path class="lifkejbvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:briefcase-dollar" /></template>
