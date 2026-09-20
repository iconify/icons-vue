<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/k/k26d2bbmf.css';
import '../../css/m/mfbnmqh5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="k26d2bbmf"/><path class="mfbnmqh5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:add-hexagon-2" /></template>
