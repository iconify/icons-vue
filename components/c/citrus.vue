<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/s-8rzmitj.css';
import '../../css/a/ay6zfx3qi.css';
import '../../css/r/rxiflsmfe.css';
import '../../css/m/m6vwfnbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="s-8rzmitj wm-shadow"/><path class="ay6zfx3qi wm-shadow"/><path class="rxiflsmfe"/><path class="m6vwfnbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:citrus" /></template>
