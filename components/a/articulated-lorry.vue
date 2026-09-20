<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k9rt8jbqm"/><path class="b436-31bc"/><path class="x1z8rhb6l"/><circle class="q7kos792t"/><circle class="c5hldabxw"/><circle class="igy6fbcnl"/><circle class="z8p62baxr"/><circle class="q3thokagc"/><circle class="dp1-ptbah"/><path class="yxj9-2zwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:articulated-lorry" /></template>
<style>
.b436-31bc {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M10 12H7.146C4 12 3 14 3 14l-3 5.959V25h13V15a3 3 0 0 0-3-3");
}

.c5hldabxw {
  cx: 6px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.dp1-ptbah {
  cx: 20px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.igy6fbcnl {
  cx: 30px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.k9rt8jbqm {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M31 25H11v-1a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v3a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-2z");
}

.q3thokagc {
  cx: 20px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.q7kos792t {
  cx: 6px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.x1z8rhb6l {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M9 20H2l2-4s1-2 3-2h2z");
}

.yxj9-2zwa {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M32 8H19a4 4 0 0 0-4 4v13h21V12a4 4 0 0 0-4-4");
}

.z8p62baxr {
  cx: 30px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

</style>
