<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v91oebczy.css';
import '../../css/r/rdg5s2amp.css';
import '../../css/o/o_0ccoams.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v91oebczy"/><path class="rdg5s2amp"/><path class="o_0ccoams"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:file-import-light" /></template>
