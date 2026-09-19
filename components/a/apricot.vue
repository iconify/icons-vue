<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h9f8jm2-z.css';
import '../../css/h/hw1b44bxw.css';
import '../../css/d/d9i98uvix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h9f8jm2-z"/><path class="hw1b44bxw"/><path class="d9i98uvix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:apricot" /></template>
