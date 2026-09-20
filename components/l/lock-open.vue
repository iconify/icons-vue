<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i1jn65byr.css';
import '../../css/z/zyfkq2bfx.css';
import '../../css/d/dgz12lltg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i1jn65byr"/><path clip-rule="evenodd" class="zyfkq2bfx"/><path class="dgz12lltg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:lock-open" /></template>
