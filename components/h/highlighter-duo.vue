<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p27m1gsns.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ox74gzd0h.css';
import '../../css/v/v96i2q43c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p27m1gsns secondary"/><g class="dt0cm9dhy primary"><path class="ox74gzd0h"/><path class="v96i2q43c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:highlighter-duo" /></template>
