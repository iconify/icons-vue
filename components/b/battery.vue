<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t5kuevs6k.css';
import '../../css/p/pgaah8bvy.css';
import '../../css/y/ypb3ww6cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><rect class="t5kuevs6k"/><path class="pgaah8bvy"/><path clip-rule="evenodd" class="ypb3ww6cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:battery" /></template>
