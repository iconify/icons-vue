<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGSSiA6b1T)" class="kjp9ytbgl"/><path fill="url(#SVGHSRcpcpH)" class="y3ooewbri"/><path fill="url(#SVG11MRCdQy)" class="rk376rbus"/><defs><linearGradient id="SVGSSiA6b1T" x1="4.5" x2="17.28" y1="6" y2="19.014" gradientUnits="userSpaceOnUse"><stop class="nsij3bu4f"/><stop offset="1" class="pc6twabtt"/></linearGradient><linearGradient id="SVGHSRcpcpH" x1="4.5" x2="22.324" y1="3" y2="7.563" gradientUnits="userSpaceOnUse"><stop class="b21bkob0c"/><stop offset="1" class="j1ybr5z-s"/></linearGradient><linearGradient id="SVG11MRCdQy" x1="5.1" x2="14.034" y1="18.9" y2="13.692" gradientUnits="userSpaceOnUse"><stop class="dt9chctwi"/><stop offset="1" class="dktnb9shj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:deso" /></template>
<style>
.b21bkob0c {
  stop-color: var(--svg-color--84c3ff, #84c3ff);
}

.dktnb9shj {
  stop-color: var(--svg-color--f6fbff, #f6fbff);
}

.dt9chctwi {
  stop-color: var(--svg-color--a8d5ff, #a8d5ff);
}

.ft5dv1b6b {
  fill: none;
}

.j1ybr5z-s {
  stop-color: var(--svg-color--fbfeff, #fbfeff);
}

.kjp9ytbgl {
  d: path("M4.5 3v4.5l11.4 6.576L4.5 21h9.282c3.162 0 5.718-2.22 5.718-4.95V12z");
}

.nsij3bu4f {
  stop-color: var(--svg-color--3fa3ff, #3fa3ff);
}

.pc6twabtt {
  stop-color: var(--svg-color--f0f8ff, #f0f8ff);
}

.rk376rbus {
  d: path("m12.21 11.946l-7.71 4.56V21l11.4-6.924z");
}

.y3ooewbri {
  d: path("m4.5 3l15 9V7.95C19.5 5.214 16.938 3 13.782 3z");
}

</style>
