<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ufdwcf-0b.css';
import '../../css/b/bekxl5b0t.css';
import '../../css/h/hi120-b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ufdwcf-0b"/><path clip-rule="evenodd" class="bekxl5b0t"/><path class="hi120-b8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bell-off" /></template>
