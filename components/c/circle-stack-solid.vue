<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bw5x8jbeo.css';
import '../../css/f/fcrg7jb_a.css';
import '../../css/h/hp5c_5epy.css';
import '../../css/v/vahsu3btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bw5x8jbeo"/><path class="fcrg7jb_a"/><path class="hp5c_5epy"/><path class="vahsu3btp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:circle-stack-solid" /></template>
