<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g clip-rule="evenodd" class="utxjc7b5q"><path class="e-4uhbt6a"/><path class="ykd2hbt2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:envelope" /></template>
<style>
.e-4uhbt6a {
  d: path("M20.97 50.92v45.02h86.06V50.92L64 72.31z");
}

.utxjc7b5q {
  fill: var(--svg-color--fcc21b, #fcc21b);
  fill-rule: evenodd;
}

.ykd2hbt2n {
  d: path("M20.97 32.06v11.98L64 65.43l43.03-21.39V32.06z");
}

</style>
