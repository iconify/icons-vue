<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yciimpb-x.css';
import '../../css/o/o0a-r_1pg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yciimpb-x"/><path class="o0a-r_1pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-music-line" /></template>
