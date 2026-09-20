<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVG5tjSqbma" width="18" height="18" x="3" y="3" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path fill="url(#SVG8Q3H5HSu)" class="mio-dr80t"/><path fill="url(#SVG8Q3H5HSu)" class="wt1qn5box"/></mask><g class="ft5dv1b6b"><path fill="url(#SVGI6UuPdPa)" class="bunzk8bpa"/><path fill="url(#SVGMLT3deNO)" class="y8hr43bmg"/><g mask="url(#SVG5tjSqbma)"><path fill="url(#SVGI0gy5YkD)" class="polrwdb1x"/></g><defs><linearGradient id="SVGI6UuPdPa" x1="18.475" x2="13.422" y1="22.238" y2=".981" gradientUnits="userSpaceOnUse"><stop class="gzzjlhbzs"/><stop offset="1" class="e1a251blk"/></linearGradient><linearGradient id="SVGMLT3deNO" x1="18.475" x2="13.423" y1="22.238" y2=".981" gradientUnits="userSpaceOnUse"><stop class="gzzjlhbzs"/><stop offset="1" class="e1a251blk"/></linearGradient><linearGradient id="SVG8Q3H5HSu" x1="18.278" x2="13.143" y1="22.238" y2="1.023" gradientUnits="userSpaceOnUse"><stop class="gzzjlhbzs"/><stop offset="1" class="e1a251blk"/></linearGradient><linearGradient id="SVGI0gy5YkD" x1="4.215" x2="13.103" y1="7.05" y2="13.688" gradientUnits="userSpaceOnUse"><stop offset=".12" class="iiy99riqp"/><stop offset="1" class="f_n61zbbd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:exodus" /></template>
<style>
.bunzk8bpa {
  d: path("M21 8.026L13.194 3v2.81l5.008 3.195l-.59 1.83h-4.418v2.33h4.419l.589 1.83l-5.008 3.195V21L21 15.99l-1.276-3.982z");
}

.e1a251blk {
  stop-color: var(--svg-color--bbfbe0, #bbfbe0);
}

.f_n61zbbd {
  stop-color: var(--svg-color--dabdff, #dabdff);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gzzjlhbzs {
  stop-color: var(--svg-color--0b46f9, #0b46f9);
}

.iiy99riqp {
  stop-color: var(--svg-color--8952ff, #8952ff);
  stop-opacity: 0.87;
}

.mio-dr80t {
  d: path("M20.758 8.026L13.092 3v2.81l4.918 3.195l-.579 1.83h-4.339v2.33h4.34l.578 1.83l-4.918 3.195V21l7.666-5.01l-1.254-3.982z");
}

.polrwdb1x {
  d: path("M20.64 3H3.09v18h17.55z");
}

.wt1qn5box {
  d: path("M6.424 13.164h4.322v-2.328H6.407l-.562-1.83l4.901-3.196V3L3.081 8.026l1.253 3.982l-1.253 3.982L10.762 21v-2.81l-4.917-3.195z");
}

.y8hr43bmg {
  d: path("M6.404 13.164h4.401v-2.328H6.387l-.572-1.83l4.99-3.196V3L3 8.026l1.276 3.982L3 15.99L10.822 21v-2.81l-5.007-3.195z");
}

</style>
