<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lghyv1bbe.css';
import '../../css/a/ao7oa23vf.css';
import '../../css/s/srlliip3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lghyv1bbe"/><path class="ao7oa23vf"/><path clip-rule="evenodd" class="srlliip3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:disc" /></template>
