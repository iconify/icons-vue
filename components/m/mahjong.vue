<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zvlf3ib2s"/><path class="gpg4vmz9k"/><path class="gollwqbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mahjong" /></template>
<style>
.gollwqbwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.58 19.84l-12.435-2.422v5.298L28.58 25.33z");
}

.gpg4vmz9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.56 43.13l3.21-2.66a1.55 1.55 0 0 0 .39-1.24l.16-30.31a2.81 2.81 0 0 0-2.69-3L21 4.56a12.3 12.3 0 0 0-3.59.13l-4.07.85m9.023 7.458v22.644");
}

.zvlf3ib2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.3 5.54L31 7.73a2.62 2.62 0 0 1 2.08 2.63v31.37A1.61 1.61 0 0 1 31 43.44l-17.36-4.63a2.27 2.27 0 0 1-2-2.39V7.05c.04-.68.36-1.4 1.66-1.51");
}

</style>
