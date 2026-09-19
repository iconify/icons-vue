<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="f_v_dfbgn"/><circle class="f_v_dfbgn"/><circle class="f_v_dfbgn"/><circle class="razo70sba"/><circle class="vgx5snbuw"/><circle class="rl7fyybai"/><circle class="pjeq8bhtm"/><path class="ug5kedb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fleksy" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.pjeq8bhtm {
  cx: 13.704px;
  cy: 24px;
  r: 5.704px;
}

.razo70sba {
  cx: 24px;
  cy: 13.704px;
  r: 5.704px;
}

.rl7fyybai {
  cx: 24px;
  cy: 34.296px;
  r: 5.704px;
}

.ug5kedb7q {
  d: path("M29.825 20.478A5.7 5.7 0 0 0 28.593 24a5.7 5.7 0 0 0 1.232 3.523l2.503-2.504a1.44 1.44 0 0 0 0-2.038zM24 28.593a5.7 5.7 0 0 0-3.522 1.232l2.503 2.503a1.44 1.44 0 0 0 2.038 0l2.51-2.51A5.7 5.7 0 0 0 24 28.594Zm-5.819-8.122l-2.51 2.51a1.44 1.44 0 0 0 0 2.038l2.504 2.503A5.7 5.7 0 0 0 19.408 24a5.7 5.7 0 0 0-1.227-3.529M24 15.248c-.369 0-.737.141-1.02.424l-2.503 2.503A5.7 5.7 0 0 0 24 19.407a5.7 5.7 0 0 0 3.523-1.232l-2.504-2.503A1.44 1.44 0 0 0 24 15.248");
}

.vgx5snbuw {
  cx: 34.296px;
  cy: 24px;
  r: 5.704px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
