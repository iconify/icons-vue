<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ki2kqmb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bundle-offer" /></template>
<style>
.ki2kqmb_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.357 4.064Q13.25 3.94 12 6.128Q10.75 3.94 8.643 4.064q-1.39.082-1.79 1.397q-.24.789.044 1.789H4.75q-2.5 0-2.5 2.5v1q0 1.036.732 1.768q.514.513 1.177.667q-.409.766-.409 1.94v3.75q0 3.375 3.375 3.375h9.75q3.375 0 3.375-3.375v-3.75q0-1.174-.409-1.94q.663-.154 1.177-.667q.732-.732.732-1.768v-1q0-1.036-.732-1.768T19.25 7.25h-2.147q.284-1 .044-1.789q-.4-1.315-1.79-1.397M10.894 7.25H8.481q-.347-.848-.193-1.352q.096-.316.444-.337q1.308-.077 2.162 1.689m4.625 0h-2.413q.854-1.766 2.162-1.689q.348.021.444.337q.154.504-.193 1.352");
}

</style>
