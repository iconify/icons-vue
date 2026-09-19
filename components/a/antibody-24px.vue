<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a82rnzv4e.css';
import '../../css/l/lz5ryfbew.css';
import '../../css/c/cmk8cnb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a82rnzv4e"/><path class="lz5ryfbew"/><path class="cmk8cnb6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:antibody-24px" /></template>
