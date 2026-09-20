<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ao6vq1b1u.css';
import '../../css/l/lu5wldhly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ao6vq1b1u"/><path clip-rule="evenodd" class="lu5wldhly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-up-bold-duotone" /></template>
