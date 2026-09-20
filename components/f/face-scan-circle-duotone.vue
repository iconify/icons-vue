<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a0idaqb9i.css';
import '../../css/p/p3ilim6vk.css';
import '../../css/r/rm3taibxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a0idaqb9i"/><path class="p3ilim6vk"/><path class="rm3taibxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:face-scan-circle-duotone" /></template>
