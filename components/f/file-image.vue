<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cg2gptb6q.css';
import '../../css/y/ymnsh4bsn.css';
import '../../css/y/ykzxdyblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="cg2gptb6q"/><path class="ymnsh4bsn"/><path class="ykzxdyblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-image" /></template>
