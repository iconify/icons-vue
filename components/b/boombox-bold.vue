<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s_61f0g-l.css';
import '../../css/f/fxu3lsbwq.css';
import '../../css/s/sbh5qwbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s_61f0g-l"/><path class="fxu3lsbwq"/><path clip-rule="evenodd" class="sbh5qwbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boombox-bold" /></template>
