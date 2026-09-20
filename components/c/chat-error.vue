<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lcg626bqg.css';
import '../../css/m/miqf99bxq.css';
import '../../css/s/s53s2kbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lcg626bqg"/><path class="miqf99bxq"/><path class="s53s2kbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chat-error" /></template>
