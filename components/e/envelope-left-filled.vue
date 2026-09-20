<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b4_vrm0lk.css';
import '../../css/i/ixp8dd_fd.css';
import '../../css/z/zanu4ibmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b4_vrm0lk"/><path class="ixp8dd_fd"/><path class="zanu4ibmw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope-left-filled" /></template>
