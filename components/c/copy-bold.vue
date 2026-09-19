<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0phu2bbs.css';
import '../../css/t/tz5aj022z.css';
import '../../css/g/gchw9w8-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tz5aj022z"/><path class="gchw9w8-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:copy-bold" /></template>
