<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="n_cbk9que"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:libra" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.n_cbk9que {
  fill: var(--svg-color--fff, #fff);
  d: path("M29 30H7a1.5 1.5 0 1 1 0-3h22a1.5 1.5 0 0 1 0 3m0-5h-8a1.5 1.5 0 0 1-.965-2.648c1.242-1.045 4.464-4.346 4.464-7.04c0-4.186-3.305-6.687-6.5-6.687s-6.5 2.478-6.5 6.625c0 2.699 3.23 6.046 4.474 7.109A1.5 1.5 0 0 1 15 25H7a1.5 1.5 0 1 1 0-3h4.465c-1.452-1.774-2.966-4.23-2.966-6.75c0-6.025 4.83-9.625 9.5-9.625c4.568 0 9.5 3.704 9.5 9.687c0 2.507-1.496 4.932-2.94 6.688H29a1.5 1.5 0 0 1 0 3");
}

</style>
