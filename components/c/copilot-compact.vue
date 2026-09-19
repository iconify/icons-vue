<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d9fyp-bah.css';
import '../../css/e/euq09ab2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="d9fyp-bah"/><path clip-rule="evenodd" class="euq09ab2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-compact" /></template>
