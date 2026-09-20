<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ausxz4bhq"/><path class="vcleb3b9g"/><path class="j6wz7fj1x"/><path class="o9evamkls"/><path class="pgo3wkbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flashlight" /></template>
<style>
.ausxz4bhq {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m23 17l1-1s1-1 2 0l2 2s1 1 0 2l-1 1z");
}

.j6wz7fj1x {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M20.879 10.879a3.01 3.01 0 0 1 0 4.242l-5.758 5.758a3.01 3.01 0 0 1-4.242 0L6 16s-1-1 0-2l8-8c1-1 2 0 2 0z");
}

.o9evamkls {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M7 17L17 7l2 2L9 19z");
}

.pgo3wkbxq {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M11.001 6a1 1 0 0 1-.896-.553l-2-4a1.001 1.001 0 0 1 1.79-.895l2 4A1 1 0 0 1 11.001 6m-6.002 6a1 1 0 0 1-.446-.106l-4-2a1 1 0 1 1 .894-1.788l4 2A1 1 0 0 1 4.999 12M8 9a1 1 0 0 1-.707-.293l-4-4a.999.999 0 1 1 1.414-1.414l4 4A.999.999 0 0 1 8 9");
}

.vcleb3b9g {
  fill: var(--svg-color--8899a6, #8899a6);
  d: path("M34.879 27.879a3.01 3.01 0 0 1 0 4.242l-2.758 2.758a3.01 3.01 0 0 1-4.242 0L9.121 16.121a3.01 3.01 0 0 1 0-4.242l2.758-2.758a3.01 3.01 0 0 1 4.242 0z");
}

</style>
