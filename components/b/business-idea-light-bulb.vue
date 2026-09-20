<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3xtuk_0z.css';
import '../../css/r/ri309n8_l.css';
import '../../css/w/w50yv1b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="l3xtuk_0z"><path class="ri309n8_l"/><path class="w50yv1b4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:business-idea-light-bulb" /></template>
