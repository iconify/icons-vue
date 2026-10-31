<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sudg71c6u.css';
import '../../css/l/l39i1pkyb.css';
import '../../css/c/cgvibbbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sudg71c6u wm-shadow"/><path class="l39i1pkyb wm-shadow"/><path class="cgvibbbrh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:anchor" /></template>
