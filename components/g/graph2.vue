<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p4gh0oh5n.css';
import '../../css/e/emkr1lb8r.css';
import '../../css/s/s-_ewh-er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p4gh0oh5n"/><path class="emkr1lb8r"/><path clip-rule="evenodd" class="s-_ewh-er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:graph2" /></template>
