<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf4u1os6q.css';
import '../../css/e/euvn5gkav.css';
import '../../css/r/r2aeg49cb.css';
import '../../css/a/a6nvfqtpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="tf4u1os6q"><path class="euvn5gkav"/><path class="r2aeg49cb"/><path class="a6nvfqtpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:docusaurus" /></template>
