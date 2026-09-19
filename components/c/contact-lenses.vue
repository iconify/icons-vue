<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fc0i6jz9j.css';
import '../../css/u/ujlvc1bor.css';
import '../../css/b/b5f5xnbyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fc0i6jz9j"/><path class="ujlvc1bor"/><path class="b5f5xnbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contact-lenses" /></template>
