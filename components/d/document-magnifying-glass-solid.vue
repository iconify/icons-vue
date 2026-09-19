<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lkzw9u2tc.css';
import '../../css/b/bg5s2xb2o.css';
import '../../css/u/ui7z5xbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lkzw9u2tc"/><path clip-rule="evenodd" class="bg5s2xb2o"/><path class="ui7z5xbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-magnifying-glass-solid" /></template>
