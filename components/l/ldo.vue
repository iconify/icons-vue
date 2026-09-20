<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGqijtqblU)" class="xq8ldfkni"/><path fill="url(#SVGdfv5pK0T)" class="dae52pbna"/><path fill="url(#SVGU6lmWc1A)" class="bem-hacgj"/><path fill="url(#SVGPB9jNmhD)" class="zs5b07foo"/><defs><linearGradient id="SVGqijtqblU" x1="11.997" x2="11.997" y1="3" y2="21.006" gradientUnits="userSpaceOnUse"><stop class="b_fvvlz7a"/><stop offset="1" class="rano1jbzh"/></linearGradient><linearGradient id="SVGdfv5pK0T" x1="11.996" x2="11.996" y1="3.015" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="dtcgcg9vz"/><stop offset=".7" class="w7rj_bcgn"/></linearGradient><linearGradient id="SVGU6lmWc1A" x1="13.325" x2="10.874" y1="13.006" y2="21.729" gradientUnits="userSpaceOnUse"><stop class="s48hmmbov"/><stop offset=".56" class="n3efd8cmk"/></linearGradient><linearGradient id="SVGPB9jNmhD" x1="8.531" x2="9.328" y1="7.767" y2="11.618" gradientUnits="userSpaceOnUse"><stop class="mz7dz8bnk"/><stop offset=".61" class="ya1zc1ykq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ldo" /></template>
<style>
.b_fvvlz7a {
  stop-color: var(--svg-color--498be9, #498be9);
}

.bem-hacgj {
  d: path("m12.002 3l4.404 6.95l-4.404 2.585z");
}

.dae52pbna {
  d: path("m17.078 11.14l-5.066 2.978L6.91 11.14l5.1-2.69z");
}

.dtcgcg9vz {
  stop-color: var(--svg-color--4a8cea, #4a8cea);
}

.ft5dv1b6b {
  fill: none;
}

.mz7dz8bnk {
  stop-color: var(--svg-color--ffe235, #ffe235);
}

.n3efd8cmk {
  stop-color: var(--svg-color--568fdd, #568fdd);
}

.rano1jbzh {
  stop-color: var(--svg-color--56f2ff, #56f2ff);
}

.s48hmmbov {
  stop-color: var(--svg-color--fb8174, #fb8174);
}

.w7rj_bcgn {
  stop-color: var(--svg-color--5abef4, #5abef4);
}

.xq8ldfkni {
  d: path("m11.997 14.129l-5.106-3l-.144.22a6.32 6.32 0 0 0 .846 7.816a6.2 6.2 0 0 0 8.808 0a6.296 6.296 0 0 0 .847-7.816l-.145-.22z");
}

.ya1zc1ykq {
  stop-color: var(--svg-color--5dcba2, #5dcba2);
}

.zs5b07foo {
  d: path("M12.002 3v9.535L7.6 9.945z");
}

</style>
