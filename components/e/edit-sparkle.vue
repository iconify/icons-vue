<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b5ukf1u_z.css';
import '../../css/s/s-f2414gw.css';
import '../../css/z/zdx0yk9nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="b5ukf1u_z"/><path clip-rule="evenodd" class="s-f2414gw"/><path class="zdx0yk9nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:edit-sparkle" /></template>
