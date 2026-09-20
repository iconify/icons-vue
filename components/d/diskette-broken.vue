<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kt1ahab5v.css';
import '../../css/a/adlaw-b6t.css';
import '../../css/o/onymejbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kt1ahab5v"/><path class="adlaw-b6t"/><path class="onymejbgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:diskette-broken" /></template>
