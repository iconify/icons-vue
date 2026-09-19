<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ydqthzbbt"/><path class="xkjslobbt"/><circle class="bou4e5bzg"/><path class="udcp88a3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:consorsbank" /></template>
<style>
.bou4e5bzg {
  cx: 28.649px;
  cy: 32.355px;
  r: 0.75px;
  fill: currentColor;
}

.udcp88a3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.649 25.271v5.269");
}

.xkjslobbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.066 19.478v.026a2.283 2.283 0 0 1-2.283 2.283h0A2.283 2.283 0 0 1 8.5 19.504v-2.326a2.283 2.283 0 0 1 2.283-2.283h0a2.283 2.283 0 0 1 2.283 2.283v.026m1.378 1.74a1.723 1.723 0 1 1 3.446 0v1.12a1.723 1.723 0 1 1-3.446 0zm9.758 2.458c.314.264.654.385 1.417.385h.386a1.14 1.14 0 0 0 1.14-1.141h0c0-.63-.51-1.142-1.14-1.142h-.773a1.14 1.14 0 0 1-1.139-1.141h0c0-.63.51-1.142 1.14-1.142h.386c.763 0 1.102.121 1.417.385m-4.321 4.181v-2.843c0-.952-.772-1.723-1.723-1.723h0c-.952 0-1.723.771-1.723 1.723m0 2.843v-4.566m14.078 1.723c0-.952.772-1.723 1.723-1.723h0m-1.723 0v4.566m-4.824-2.843a1.723 1.723 0 1 1 3.446 0v1.12a1.723 1.723 0 1 1-3.446 0zm8.034 2.458c.315.264.655.385 1.417.385h.387a1.14 1.14 0 0 0 1.139-1.141h0c0-.63-.51-1.142-1.139-1.142h-.773a1.14 1.14 0 0 1-1.14-1.141h0c0-.63.51-1.142 1.14-1.142h.386c.763 0 1.103.121 1.417.385M8.5 29.654c0-.978.793-1.77 1.771-1.77h0a1.77 1.77 0 0 1 1.771 1.77v1.151c0 .978-.793 1.771-1.771 1.771h0a1.77 1.77 0 0 1-1.771-1.77m0 1.77v-7.084m8.5 5.313a1.77 1.77 0 0 1-1.77 1.771h0a1.77 1.77 0 0 1-1.771-1.77v-1.152c0-.978.792-1.77 1.77-1.77h0a1.77 1.77 0 0 1 1.772 1.77m0 2.922v-4.693m4.823 4.693v-2.81c0-.94-.763-1.704-1.704-1.704h0c-.94 0-1.703.763-1.703 1.704m0 2.81v-4.514m4.824-2.57v7.084m0-1.504l3.207-3.191m-2.186 2.175l2.52 2.51");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

</style>
