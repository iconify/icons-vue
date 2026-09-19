<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w0kto8s3b.css';
import '../../css/x/x2wo05btj.css';
import '../../css/l/lupto5cbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="w0kto8s3b"/><path class="x2wo05btj"/><path clip-rule="evenodd" class="lupto5cbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:cook" /></template>
