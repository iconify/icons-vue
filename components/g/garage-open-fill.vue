<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iiq-4cb7m"/><path class="zql7q7g6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:garage-open-fill" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iiq-4cb7m {
  fill-rule: evenodd;
  d: path("M22 8C22.552 8 23 8.447 23 9V21C23 22.104 22.105 23 21 23H3C1.8954 23 1 22.104 1 21V9C1 8.447 1.4477 8 2 8H22ZM8 11C6.8955 11 6.0002 11.895 6 13V21H18V13C17.9998 11.895 17.1045 11 16 11H8Z");
}

.zql7q7g6d {
  d: path("M11.0879 1.219C11.6603 0.926 12.3397 0.926 12.9121 1.219L21.1299 5.43C21.4094 5.576 21.3062 6 20.9902 6H3.0098C2.6941 6 2.5906 5.576 2.8691 5.43L11.0879 1.219Z");
}

</style>
