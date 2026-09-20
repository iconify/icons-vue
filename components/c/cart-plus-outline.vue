<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l7ghpebcu.css';
import '../../css/x/x59fuv1nw.css';
import '../../css/p/p-nzwk9jc.css';
import '../../css/g/gewiseacf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l7ghpebcu"/><path clip-rule="evenodd" class="x59fuv1nw"/><path clip-rule="evenodd" class="p-nzwk9jc"/><path clip-rule="evenodd" class="gewiseacf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-plus-outline" /></template>
