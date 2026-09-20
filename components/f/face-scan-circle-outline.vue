<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lnnhast9d.css';
import '../../css/g/gamqvlbit.css';
import '../../css/t/t1hqvdscu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lnnhast9d"/><path class="gamqvlbit"/><path clip-rule="evenodd" class="t1hqvdscu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:face-scan-circle-outline" /></template>
