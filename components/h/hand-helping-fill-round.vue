<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktj87dkwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-helping-fill-round" /></template>
<style>
.ktj87dkwt {
  fill: currentColor;
  d: path("M13 17h-3a1.002 1.002 0 0 1-1.707.707l-6-6a.999.999 0 1 1 1.414-1.414l.293.293l2.293-2.293C7.049 7.537 7.896 7 9 7h3c.942 0 1.827.439 2.394 1.191l1.899-1.898a3.121 3.121 0 1 1 4.414 4.414l-5 5C14.992 16.422 14.039 17 13 17m-1-4h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 0-2H9c-.524 0-.941.356-1.293.707L5.414 12l3 3H13c.468 0 .98-.395 1.293-.707l5-5a1.121 1.121 0 1 0-1.586-1.586l-2.74 2.74A3 3 0 0 1 12 13");
}

</style>
