<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="u-glmf45e"><path class="kj79l_b5s"/><path class="mbrhu7biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cgt" /></template>
<style>
.kj79l_b5s {
  d: path("M12.67 20.218V15.4a3.36 3.36 0 0 1-3.19-4.162a3.316 3.316 0 0 1 3.066-2.553a3.36 3.36 0 0 1 3.558 3.24H21c0-1.625-.556-3.14-1.46-4.491A8.218 8.218 0 0 0 4.92 9.38H3v5.095h1.872a8.22 8.22 0 0 0 3.27 4.358a8.1 8.1 0 0 0 4.529 1.385");
}

.mbrhu7biy {
  d: path("M19.288 19.662a3.054 3.054 0 1 1 1.044-4.296l-1.33.76a1.527 1.527 0 1 0-.103 1.908h-.629v-1.018h2.545v3.054h-1.527z");
}

.u-glmf45e {
  fill: var(--svg-color--f7b600, #f7b600);
}

</style>
