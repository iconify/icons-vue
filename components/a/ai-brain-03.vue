<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cjuia-bgq.css';
import '../../css/w/wi-0c7-en.css';
import '../../css/b/b3zeicc3h.css';
import '../../css/p/px8h8ibau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cjuia-bgq"/><path class="wi-0c7-en"/><path class="b3zeicc3h"/><path class="px8h8ibau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-brain-03" /></template>
