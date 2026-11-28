<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p514r1kdi.css';
import '../../css/w/we76hrb5m.css';
import '../../css/b/br-iwyzus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p514r1kdi"/><path class="we76hrb5m"/><path class="br-iwyzus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:book-stack" /></template>
