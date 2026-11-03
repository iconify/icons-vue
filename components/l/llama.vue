<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlb6a3l8z.css';
import '../../css/i/ih3ngibul.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/dau0ygbea.css';
import '../../css/u/ugmww1bhr.css';
import '../../css/j/jvyq_hbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vlb6a3l8z"/><path class="ih3ngibul"/><g class="jn8qy4bru"><path class="dau0ygbea"/><path class="ugmww1bhr"/><path class="jvyq_hbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:llama" /></template>
