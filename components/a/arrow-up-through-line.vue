<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i3-29jb8c.css';
import '../../css/g/g25wxlbyx.css';
import '../../css/d/dvfmgjbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i3-29jb8c"/><path class="g25wxlbyx"/><path class="dvfmgjbui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-through-line" /></template>
