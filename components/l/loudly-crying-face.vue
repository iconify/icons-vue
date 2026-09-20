<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ngpmpqbbo"/><path class="q0a9x69gb"/><path class="cq956yb0y"/><path class="ezb49gsoo"/><ellipse class="biuehmbow"/><ellipse class="t2_n0_roz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:loudly-crying-face" /></template>
<style>
.biuehmbow {
  cx: 18px;
  cy: 34px;
  fill: var(--svg-color--5dadec, #5dadec);
  rx: 18px;
  ry: 2px;
}

.cq956yb0y {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M24 16h4v19l-4-.046zM8 35l4-.046V16H8z");
}

.ezb49gsoo {
  fill: var(--svg-color--664500, #664500);
  d: path("M14.999 18c-.15 0-.303-.034-.446-.105c-3.512-1.756-7.07-.018-7.105 0a1 1 0 1 1-.895-1.789c.182-.09 4.498-2.197 8.895 0A1 1 0 0 1 14.999 18m14 0c-.15 0-.303-.034-.446-.105c-3.513-1.756-7.07-.018-7.105 0a1 1 0 1 1-.895-1.789c.182-.09 4.501-2.196 8.895 0A1 1 0 0 1 28.999 18");
}

.ngpmpqbbo {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18S0 27.941 0 18S8.059 0 18 0s18 8.059 18 18");
}

.q0a9x69gb {
  fill: var(--svg-color--664500, #664500);
  d: path("M22 27c0 2.763-1.791 3-4 3s-4-.237-4-3c0-2.761 1.79-6 4-6s4 3.239 4 6m8-12a1 1 0 0 1-.371-.072c-5.229-2.091-7.372-5.241-7.461-5.374a1 1 0 0 1 1.662-1.113c.019.027 1.93 2.785 6.541 4.629A1 1 0 0 1 30 15M6 15a1.001 1.001 0 0 1-.372-1.929c4.612-1.844 6.523-4.602 6.542-4.629a1 1 0 0 1 1.387-.27a1 1 0 0 1 .275 1.383c-.089.133-2.232 3.283-7.46 5.374A1 1 0 0 1 6 15");
}

.t2_n0_roz {
  cx: 18px;
  cy: 27px;
  fill: var(--svg-color--e75a70, #e75a70);
  rx: 3px;
  ry: 2px;
}

</style>
