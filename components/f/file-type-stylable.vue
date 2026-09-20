<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGXn4mTbxv" x1="-1947.843" x2="-1947.706" y1="-2006.674" y2="-2005.516" gradientTransform="matrix(12.867 0 0 21.023 25072.473 42188.473)" gradientUnits="userSpaceOnUse"><stop offset="0" class="f8i8c1-xs"/><stop offset=".536" class="pcq--tb9c"/><stop offset="1" class="t1vpry1bs"/></linearGradient><linearGradient id="SVGuU6TZDMX" x1="-1958.897" x2="-1959.478" y1="-1999.713" y2="-1998.526" gradientTransform="matrix(12.805 0 0 21.012 25107.678 42025.3)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mhjgombvz"/><stop offset="1" class="vo483ac5c"/></linearGradient></defs><path fill="url(#SVGXn4mTbxv)" class="lfp-dlbyu"/><path class="l50bwdylh"/><path class="ixkoiq42l"/><path class="y666xs0qq"/><path fill="url(#SVGuU6TZDMX)" class="fsnwlkpbg"/><path class="gtssoj00o"/><path class="bl6cxp8ve"/><path class="xdv6xxlnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-stylable" /></template>
<style>
.bl6cxp8ve {
  fill: var(--svg-color--670010, #670010);
  d: path("M19.258 12.016a2.224 2.224 0 0 0 .3 3.1a4.77 4.77 0 0 1 1.7 4a4.1 4.1 0 0 1-.5 2.4c2.7-3 3.6-8.792.4-10.191a1.54 1.54 0 0 0-1.9.691");
}

.f8i8c1-xs {
  stop-color: var(--svg-color--7ad852, #7ad852);
}

.fsnwlkpbg {
  d: path("M18.758 30a3.15 3.15 0 0 1-2.4-1.1a2.673 2.673 0 0 1 .7-4.2c1.9-1.3 3.4-2.9 3.5-5.2c0-2.3-1.6-3.8-3.5-5.2a2.9 2.9 0 0 1-.7-4.3a3.15 3.15 0 0 1 2.4-1.1a6.6 6.6 0 0 1 2.3.5c2.4 1 7.793 5.895 7.893 9.991c0 3.9-5.5 8.992-7.893 9.991a5.2 5.2 0 0 1-2.3.618");
}

.gtssoj00o {
  fill: var(--svg-color--470000, #470000);
  d: path("M16.26 10.018a2.82 2.82 0 0 0 .8 4.3c2.3 1.6 3.4 3.3 3.4 5.2a5.6 5.6 0 0 1-1.8 3.9c5.5-3.9 5.995-11.989.9-14.287a3.04 3.04 0 0 0-3.3.887");
  opacity: var(--svg-opacity--0-6, 0.6);
}

.ixkoiq42l {
  fill: var(--svg-color--00418e, #00418e);
  d: path("M13.042 19.784a2.325 2.325 0 0 0-.3-3.1a4.77 4.77 0 0 1-1.7-4a4.26 4.26 0 0 1 1.1-2.7c-3.4 3.9-4.4 8.992-1.1 10.591a1.92 1.92 0 0 0 2-.791");
}

.l50bwdylh {
  fill: var(--svg-color--005892, #005892);
  d: path("M15.44 21.882a2.97 2.97 0 0 0-.5-4.5c-2.3-1.5-3.5-3-3.5-4.9a5.6 5.6 0 0 1 1.8-3.9c-5.3 5.695-5.995 11.989-.9 14.287a2.745 2.745 0 0 0 3.1-.987");
}

.lfp-dlbyu {
  d: path("M10.944 2.5c-2.4 1-7.893 5.995-7.893 9.991c0 4.1 5.5 8.992 7.893 9.991a7.1 7.1 0 0 0 2.3.5a2.9 2.9 0 0 0 2.2-1.2a3.03 3.03 0 0 0-.5-4.5c-1.9-1.3-3.4-2.5-3.5-4.8c0-2.3 1.6-3.9 3.5-5.2a2.673 2.673 0 0 0 .7-4.2a3.01 3.01 0 0 0-2.4-1.1a7.1 7.1 0 0 0-2.3.518");
}

.mhjgombvz {
  stop-color: var(--svg-color--ff2953, #ff2953);
}

.pcq--tb9c {
  stop-color: var(--svg-color--3ab38b, #3ab38b);
}

.t1vpry1bs {
  stop-color: var(--svg-color--00bfc9, #00bfc9);
}

.vo483ac5c {
  stop-color: var(--svg-color--ea3333, #ea3333);
}

.xdv6xxlnw {
  fill: var(--svg-color--730000, #730000);
  d: path("M20.756 13.515a1.54 1.54 0 0 0 .2 2a4.3 4.3 0 0 1 1.3 2.5a5 5 0 0 1-.1 1.3c.4-.7 2.2-5.6-.1-6.294a1.38 1.38 0 0 0-1.3.494");
}

.y666xs0qq {
  fill: var(--svg-color--002355, #002355);
  d: path("M11.543 18.285a1.54 1.54 0 0 0-.2-2a3.33 3.33 0 0 1-1.1-2.6c0-.9.3-1.8-.2-.7s-1.9 4.7.2 5.695a1.13 1.13 0 0 0 1.3-.395");
}

</style>
