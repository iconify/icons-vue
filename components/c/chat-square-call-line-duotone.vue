<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cwdjznwva.css';
import '../../css/l/lmjzr2g6g.css';
import '../../css/r/rwct17yif.css';
import '../../css/e/eq3frqb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cwdjznwva"/><path class="lmjzr2g6g"/><path class="rwct17yif"/><path class="eq3frqb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-call-line-duotone" /></template>
