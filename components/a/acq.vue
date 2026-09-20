<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGH2Guxe2g)" clip-rule="evenodd" class="qqqa0_gae"/><path class="vo6b2uhma"/><path class="osss9se0o"/><defs><linearGradient id="SVGH2Guxe2g" x1="15.971" x2="8.029" y1="4.059" y2="19.677" gradientUnits="userSpaceOnUse"><stop class="b0rplgbzy"/><stop offset=".5" class="oxl9mgb0b"/><stop offset="1" class="hzt-t94xd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acq" /></template>
<style>
.b0rplgbzy {
  stop-color: var(--svg-color--837dba, #837dba);
}

.ft5dv1b6b {
  fill: none;
}

.hzt-t94xd {
  stop-color: var(--svg-color--56bcaf, #56bcaf);
}

.osss9se0o {
  fill: var(--svg-color--44b4ac, #44b4ac);
  d: path("M10.94 11.736v-.794h6.883l-3.97 6.353l-2.118-3.441h1.059l1.059 1.853l2.382-3.971z");
}

.oxl9mgb0b {
  stop-color: var(--svg-color--0f67a3, #0f67a3);
}

.qqqa0_gae {
  fill-rule: evenodd;
  d: path("M12 19.941a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.vo6b2uhma {
  fill: var(--svg-color--44b4ac, #44b4ac);
  d: path("M13.588 12.264v.794H6.706l3.97-6.352l2.118 3.44h-1.059l-1.059-1.852l-2.382 3.97z");
}

</style>
