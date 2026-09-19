<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/eg6ampbwl.css';
import '../../css/f/fx9knvb4h.css';
import '../../css/c/cmpm5kb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="eg6ampbwl"/><path class="fx9knvb4h"/><path clip-rule="evenodd" class="cmpm5kb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-o-p" /></template>
