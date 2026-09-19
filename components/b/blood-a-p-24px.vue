<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rfnphpyms.css';
import '../../css/e/ekf464gcd.css';
import '../../css/r/rb4mrx5mp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rfnphpyms"/><path class="ekf464gcd"/><path clip-rule="evenodd" class="rb4mrx5mp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-a-p-24px" /></template>
