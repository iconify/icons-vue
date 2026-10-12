<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/az6csdqgz.css';
import '../../css/k/kmcgoyf5b.css';
import '../../css/j/jm1lb0omt.css';
import '../../css/d/dswk5-x-u.css';
import '../../css/s/s805e4aqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="az6csdqgz"/><path class="kmcgoyf5b"/><path class="jm1lb0omt"/><path class="dswk5-x-u"/><path class="s805e4aqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:id-card-duotone" /></template>
