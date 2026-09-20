<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o7ougp03f"/><path class="wjbamqk7d"/><path class="l37-4bokw"/><path class="fa-1bbk8h"/><path class="s0d1j_brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bed" /></template>
<style>
.fa-1bbk8h {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M32 23H4a2 2 0 0 0-2 2v4h32v-4a2 2 0 0 0-2-2");
}

.l37-4bokw {
  fill: var(--svg-color--269, #269);
  d: path("M32 23H4a2 2 0 0 0-2 2v4h32v-4a2 2 0 0 0-2-2");
}

.o7ougp03f {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M1 28h34v5H1z");
}

.s0d1j_brh {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M2.126 19.938c-.261 1.073 1.485 2.419 3.9 3.006s4.584.192 4.846-.881c.261-1.073-1.485-2.419-3.9-3.007c-2.415-.587-4.585-.192-4.846.882");
}

.wjbamqk7d {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M36 35a1 1 0 1 1-2 0V21a1 1 0 1 1 2 0zM0 35a1 1 0 1 0 2 0V13a1 1 0 1 0-2 0z");
}

</style>
