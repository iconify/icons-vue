<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tbli70boo.css';
import '../../css/h/hhkbedc5d.css';
import '../../css/v/vnor8oomw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tbli70boo"/><path class="hhkbedc5d"/><path class="vnor8oomw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:asteroid-bold" /></template>
