<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bxiujei5b.css';
import '../../css/q/qrlq0qbok.css';
import '../../css/s/s7vwfzb4c.css';
import '../../css/d/d0tiy9blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bxiujei5b"/><path class="qrlq0qbok wm-k"/><path class="s7vwfzb4c wm-a"/><path class="d0tiy9blv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-down-sketch" /></template>
