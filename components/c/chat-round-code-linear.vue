<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/snto2-zvc.css';
import '../../css/g/gu3kiwldn.css';
import '../../css/r/r6t4zeiqh.css';
import '../../css/p/p5k2ipb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="snto2-zvc"/><path class="gu3kiwldn"/><path class="r6t4zeiqh"/><path class="p5k2ipb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-code-linear" /></template>
