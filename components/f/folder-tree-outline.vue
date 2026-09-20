<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b2onxacdt.css';
import '../../css/e/ez9076b0z.css';
import '../../css/f/fgubyacio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="b2onxacdt"/><path class="ez9076b0z"/><path clip-rule="evenodd" class="fgubyacio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-outline" /></template>
