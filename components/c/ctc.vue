<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1mjunbsu"><path class="iubrm6cxt"/><path class="n2uhztpya"/><path class="v8rbfkbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctc" /></template>
<style>
.iubrm6cxt {
  d: path("m19.2 8.647l-2.02.62a6.14 6.14 0 0 0-5.72-3.45c-4.342 0-6.21 3.708-6.21 6.183c0 1.952 1.384 6.193 6.188 6.193c3.594 0 5.501-2.886 5.743-3.398l2.132.507c-.197.77-2.616 5.13-7.853 5.13C6.791 20.432 3 16.658 3 12s3.791-8.432 8.46-8.432c4.675 0 7.279 3.6 7.74 5.08");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n2uhztpya {
  d: path("M12.5 10.88H21v2.25h-8.5z");
}

.v8rbfkbut {
  d: path("M11.437 13.693a1.688 1.688 0 1 0 0-3.375a1.688 1.688 0 0 0 0 3.375");
}

</style>
