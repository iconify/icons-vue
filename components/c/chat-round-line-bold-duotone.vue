<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wr-u5pbye.css';
import '../../css/i/i8zp6bckl.css';
import '../../css/r/rm076e2fp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wr-u5pbye"/><path class="i8zp6bckl"/><path class="rm076e2fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-line-bold-duotone" /></template>
