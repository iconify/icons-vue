<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qjpvqqu5m"/><path class="annf-9bwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cupcake-bulk-round" /></template>
<style>
.annf-9bwi {
  d: path("M4.03 7.391a6 6 0 0 1 9.092-4.515a4.507 4.507 0 0 1 5.789 3.364c.709.277 1.34.721 1.839 1.296a4.812 4.812 0 0 1-1.255 7.333a.999.999 0 1 1-.99-1.738c1.028-.585 1.555-1.66 1.388-2.83s-.974-2.054-2.124-2.328a1 1 0 0 1-.768-.927a2.5 2.5 0 0 0-2.345-2.384a2.45 2.45 0 0 0-1.226.241A1 1 0 0 1 12.4 4.8a4 4 0 0 0-3.956-.486A4 4 0 0 0 6 8a1 1 0 0 1-.584.909c-.414.19-.768.49-1.006.88a2.36 2.36 0 0 0 0 2.422c.238.39.592.69 1.006.88a.999.999 0 1 1-.832 1.818a4.3 4.3 0 0 1-1.882-1.656a4.36 4.36 0 0 1 0-4.506A4.16 4.16 0 0 1 4.03 7.391M9 21v-7a1 1 0 0 1 2 0v7a1 1 0 0 1-2 0m4 0v-7a1 1 0 0 1 2 0v7a1 1 0 0 1-2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.qjpvqqu5m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.03 7.391a6 6 0 0 1 9.092-4.515a4.507 4.507 0 0 1 5.789 3.364c3.52 1.383 4.085 6.208.986 8.375l-.916 4.581c-.145.709-.43 1.401-.931 1.933A2.78 2.78 0 0 1 16 22H8a2.78 2.78 0 0 1-2.05-.871c-.501-.531-.786-1.222-.93-1.93l-.908-4.539a4.304 4.304 0 0 1-1.41-5.913A4.16 4.16 0 0 1 4.03 7.391");
}

</style>
