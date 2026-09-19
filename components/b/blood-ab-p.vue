<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q11bttj1x.css';
import '../../css/z/zycrkcc6i.css';
import '../../css/w/w-36d1b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="q11bttj1x"/><path clip-rule="evenodd" class="zycrkcc6i"/><path class="w-36d1b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-ab-p" /></template>
