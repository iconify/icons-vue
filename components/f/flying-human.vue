<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/h1m10_v9q.css';
import '../../css/h/hl3-0tb6x.css';
import '../../css/j/j55g2km1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="h1m10_v9q"/><path class="hl3-0tb6x"/><path class="j55g2km1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:flying-human" /></template>
