<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sx571qbiw.css';
import '../../css/w/w9qq0ybth.css';
import '../../css/g/gfvbhrbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sx571qbiw"/><path clip-rule="evenodd" class="w9qq0ybth"/><path clip-rule="evenodd" class="gfvbhrbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-line-24px" /></template>
