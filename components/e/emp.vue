<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGrayvPe6y)" class="ialt0zy0z"/><path fill="url(#SVG8NoWVAEJ)" class="u6m9bxywa"/><path fill="url(#SVGzOi2oc5Y)" class="ey7lpnb-l"/><defs><linearGradient id="SVGrayvPe6y" x1="6.713" x2="18.084" y1="18.598" y2="13.719" gradientUnits="userSpaceOnUse"><stop class="av23mpzvt"/><stop offset=".48" class="j91mgcc6f"/><stop offset="1" class="zadwo3blv"/></linearGradient><linearGradient id="SVG8NoWVAEJ" x1="12.039" x2="12.039" y1="3" y2="21.005" gradientUnits="userSpaceOnUse"><stop class="ha6ww_7hp"/><stop offset=".67" class="di7jzf57k"/></linearGradient><linearGradient id="SVGzOi2oc5Y" x1="21.19" x2="3.231" y1="14.434" y2="15.199" gradientUnits="userSpaceOnUse"><stop class="d4luc0bfu"/><stop offset=".41" class="w0r0mmb8n"/><stop offset=".69" class="pl86uub7t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:emp" /></template>
<style>
.av23mpzvt {
  stop-color: var(--svg-color--0031a5, #0031a5);
}

.d4luc0bfu {
  stop-color: var(--svg-color--03ddfe, #03ddfe);
}

.di7jzf57k {
  stop-color: var(--svg-color--05207d, #05207d);
}

.ey7lpnb-l {
  d: path("M20.999 11.999A9 9 0 0 1 3.45 14.81h5.737l.287.253c.855.76 2.47 2.182 4.96 2.182c3.19 0 6.002-3.183 6.002-6.372c0-1.361-.281-2.503-.63-3.353A8.96 8.96 0 0 1 21 12");
}

.ft5dv1b6b {
  fill: none;
}

.ha6ww_7hp {
  stop-color: var(--svg-color--00baff, #00baff);
}

.ialt0zy0z {
  d: path("M8.626 14.25H3.282A9 9 0 0 1 3.001 12c0-4.973 3.988-9 8.91-9H21l-2.785 2.627l-.073-.034z");
}

.j91mgcc6f {
  stop-color: var(--svg-color--009eef, #009eef);
}

.pl86uub7t {
  stop-color: var(--svg-color--00136c, #00136c);
}

.u6m9bxywa {
  d: path("M20.999 11.999A9 9 0 0 1 5.7 18.422l3.487-3.61A3.98 3.98 0 0 0 12 15.935a3.938 3.938 0 0 0 3.121-6.339l.253-.225l3.353-3.352a8.97 8.97 0 0 1 2.272 5.979");
}

.w0r0mmb8n {
  stop-color: var(--svg-color--0058c1, #0058c1);
}

.zadwo3blv {
  stop-color: var(--svg-color--009dee, #009dee);
}

</style>
