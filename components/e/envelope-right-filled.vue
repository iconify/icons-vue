<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b4_vrm0lk.css';
import '../../css/f/f7hp6ub0o.css';
import '../../css/e/e1bwoaccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4_vrm0lk"/><path class="f7hp6ub0o"/><path class="e1bwoaccw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-right-filled" /></template>
