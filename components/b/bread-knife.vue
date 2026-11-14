<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-b40p1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bread-knife" /></template>
<style>
.v7-b40p1p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.995 9.702l5.876-5.876q.732-.732 1.764-.653l2.662.205q.83.064 1.351.713q.521.65.403 1.474l-.039.272q-.222 1.553-1.785 1.695q-.349.032-.381.382q-.146 1.594-1.74 1.739q-.35.032-.382.382q-.145 1.594-1.738 1.74q-.351.032-.383.382q-.145 1.594-1.74 1.739l-.175.016q-.014.001-.023.013q-.009.011-.008.026q.079.727-.579 1.042t-1.174-.2l-1.909-1.909q-.66-.659-.66-1.591t.66-1.591m-5.48 7.248q-.733.732-.733 1.767q0 1.036.733 1.768q.732.733 1.767.733q1.036 0 1.768-.733l2.121-2.121q.733-.732.733-1.768q0-1.035-.733-1.767q-.732-.733-1.767-.733q-1.036 0-1.768.733z");
}

</style>
