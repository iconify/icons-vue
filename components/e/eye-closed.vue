<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fpmem3w0t.css';
import '../../css/n/ng9vtx4ft.css';
import '../../css/h/h4t313bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fpmem3w0t"/><path class="ng9vtx4ft"/><path class="h4t313bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:eye-closed" /></template>
