<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rn_0s_bdl.css';
import '../../css/r/rzq8dvbgl.css';
import '../../css/q/q1ijj6hsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn_0s_bdl"/><path class="rzq8dvbgl"/><path class="q1ijj6hsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:board-game-jenga" /></template>
