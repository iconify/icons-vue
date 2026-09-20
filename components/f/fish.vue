<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/svknz3bwq.css';
import '../../css/n/npr06hbbs.css';
import '../../css/b/bek0hpq9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="svknz3bwq"/><path class="npr06hbbs"/><path class="bek0hpq9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fish" /></template>
