<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m9ryynb4c.css';
import '../../css/f/fmn04bicb.css';
import '../../css/g/gjxjpib_z.css';
import '../../css/i/i30jjrboj.css';
import '../../css/p/p0ic4mbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="m9ryynb4c"/><path class="fmn04bicb"/><path class="gjxjpib_z"/><path class="i30jjrboj"/><path class="p0ic4mbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:contract-off" /></template>
