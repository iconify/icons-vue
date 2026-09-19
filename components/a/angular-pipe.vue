<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf4u1os6q.css';
import '../../css/f/f-8rhabij.css';
import '../../css/e/edskbpa8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="f-8rhabij"/><path class="edskbpa8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:angular-pipe" /></template>
