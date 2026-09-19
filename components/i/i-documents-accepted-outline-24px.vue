<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s2yfbrnjl.css';
import '../../css/s/s44rk8z4u.css';
import '../../css/e/e8odqpb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s2yfbrnjl"/><path clip-rule="evenodd" class="s44rk8z4u"/><path class="e8odqpb8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:i-documents-accepted-outline-24px" /></template>
