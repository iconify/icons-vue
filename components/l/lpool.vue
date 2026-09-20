<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGo8l5GuLk)" class="f61bmobux"/><path fill="url(#SVGGnRBHdaI)" class="rnpm07t0c"/><defs><linearGradient id="SVGo8l5GuLk" x1="5.701" x2="11.456" y1="8.683" y2="20.326" gradientUnits="userSpaceOnUse"><stop offset=".18" class="zv_-j6t7x"/><stop offset=".49" class="xlf5mjbqk"/><stop offset=".89" class="ebi6dnb2y"/></linearGradient><linearGradient id="SVGGnRBHdaI" x1="3.927" x2="20.217" y1="13.678" y2="11.973" gradientUnits="userSpaceOnUse"><stop offset=".12" class="k14t_3bcm"/><stop offset=".79" class="hg0trvmhg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lpool" /></template>
<style>
.ebi6dnb2y {
  stop-color: var(--svg-color--fe4c38, #fe4c38);
}

.f61bmobux {
  d: path("M15.524 16.897L7.402 8.671l.9-1.602l7.888 8.105z");
}

.ft5dv1b6b {
  fill: none;
}

.hg0trvmhg {
  stop-color: var(--svg-color--ff443b, #ff443b);
}

.k14t_3bcm {
  stop-color: var(--svg-color--f9c213, #f9c213);
}

.rnpm07t0c {
  d: path("M7.95 7.05c.122 0 .239.004.36.013l-.707 1.805a3.15 3.15 0 1 0 3.488 3.375l.054-.135V12a4.927 4.927 0 1 1 4.374 4.896l.67-1.72l-.044-.026a3.15 3.15 0 1 0-3.24-3.303l-.005.018V12a4.95 4.95 0 1 1-4.95-4.95");
}

.xlf5mjbqk {
  stop-color: var(--svg-color--312d2e, #312d2e);
}

.zv_-j6t7x {
  stop-color: var(--svg-color--faa31c, #faa31c);
}

</style>
