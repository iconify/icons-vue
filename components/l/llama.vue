<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlb6a3l8z.css';
import '../../css/i/ih3ngibul.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/d/db3zqophh.css';
import '../../css/k/krg836bnm.css';
import '../../css/u/uv-9pkbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vlb6a3l8z"/><path class="ih3ngibul"/><g class="jn8qy4bru"><path class="db3zqophh"/><path class="krg836bnm"/><path class="uv-9pkbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:llama" /></template>
