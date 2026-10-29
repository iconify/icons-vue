<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0dsan2jy.css';
import '../../css/q/q4i1mm1-a.css';
import '../../css/t/tqnz3b5ap.css';
import '../../css/d/dahalbmwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0dsan2jy wm-k"/><path class="q4i1mm1-a wm-k"/><path class="tqnz3b5ap wm-a"/><path class="dahalbmwa wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:images" /></template>
