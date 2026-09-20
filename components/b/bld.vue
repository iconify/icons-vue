<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="szc3d_b7q"><path class="aa8vh0b8q"/><path clip-rule="evenodd" class="y26p-6aeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bld" /></template>
<style>
.aa8vh0b8q {
  d: path("M3 10.155h3.692v3.692H3z");
}

.szc3d_b7q {
  fill: var(--svg-color--bb2d40, #bb2d40);
}

.y26p-6aeh {
  fill-rule: evenodd;
  d: path("M21 6.462H9.923v11.076H21zm-3.692 3.692h-3.692v3.692h3.692z");
}

</style>
