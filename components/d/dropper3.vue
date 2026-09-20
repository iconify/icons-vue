<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bgl1wz4_k.css';
import '../../css/t/tsh0j704h.css';
import '../../css/j/j5o3tkw7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bgl1wz4_k"/><path class="tsh0j704h"/><path clip-rule="evenodd" class="j5o3tkw7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dropper3" /></template>
