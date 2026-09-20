<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGmfRkbeCV" x1=".069" x2="1.069" y1="31.569" y2="31.569" gradientTransform="matrix(0 29.091 29.091 0 -902.364 -.545)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="SVGb1JdjVMV" x1=".069" x2="1.069" y1="31.194" y2="31.194" href="#SVGmfRkbeCV"/><mask id="SVGmWebYlEV" width="29.091" height="29.091" x="1.455" y="1.455" maskUnits="userSpaceOnUse"><path class="rg-irtbtl"/></mask></defs><g mask="url(#SVGmWebYlEV)"><path class="nib7xn_nn"/><path class="xxyl10b5k"/><path class="n8aroe0no"/><path class="hotpzkb3h"/><path class="qcpwf5jbg"/><path class="y6hacsbqt"/><path class="ynzpjdbfo"/><path class="ceego9b8r"/><path class="xh09pvbbq"/><g class="xyjtgccot"><path fill="url(#SVGmfRkbeCV)" class="amyph0bgb"/><path fill="url(#SVGb1JdjVMV)" class="z3zfb1pya"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-azurepipelines" /></template>
<style>
.amyph0bgb {
  d: path("m5.7 20.974l1.464-1.565l1.819 1.819L7.5 22.707L9.293 24.5l1.479-1.479l1.828 1.831l-1.449 1.448l4.242 4.242h6.667a1.21 1.21 0 0 0 1.212-1.212v-9.7l6.195-4.129a2.42 2.42 0 0 0 1.078-2.016V2.667a1.21 1.21 0 0 0-1.212-1.212H18.509a2.42 2.42 0 0 0-2.016 1.078l-4.129 6.194h-9.7A1.21 1.21 0 0 0 1.455 9.94v6.666Z");
}

.ceego9b8r {
  fill: var(--svg-color--0a44c2, #0a44c2);
  d: path("M23.273 12.364a3.636 3.636 0 1 0-3.636-3.636a3.636 3.636 0 0 0 3.636 3.636");
}

.hotpzkb3h {
  fill: var(--svg-color--2560e0, #2560e0);
  d: path("M6.7 18.952a1.21 1.21 0 0 1-.151-1.53l9.94-14.889a2.42 2.42 0 0 1 2.016-1.078h10.828a1.21 1.21 0 0 1 1.212 1.212v10.825a2.42 2.42 0 0 1-1.078 2.016l-14.889 9.94a1.21 1.21 0 0 1-1.53-.151Z");
}

.n8aroe0no {
  fill: var(--svg-color--062aa9, #062aa9);
  d: path("M6 18.249L17.212 1.455h13.333v13.333L13.751 26Z");
}

.nib7xn_nn {
  fill: var(--svg-color--91b0f2, #91b0f2);
  d: path("M1.455 23.273h2.181v5.091h5.091v2.182H1.455Z");
}

.qcpwf5jbg {
  fill: var(--svg-color--0a44c2, #0a44c2);
  d: path("m7.5 22.707l9.255-9.255l1.792 1.792L9.293 24.5Z");
}

.rg-irtbtl {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.7 20.974l1.464-1.565l1.819 1.819L7.5 22.707L9.293 24.5l1.479-1.479l1.828 1.831l-1.449 1.448l4.242 4.242h6.667a1.21 1.21 0 0 0 1.212-1.212v-9.7l6.195-4.129a2.42 2.42 0 0 0 1.078-2.016V2.667a1.21 1.21 0 0 0-1.212-1.212H18.509a2.42 2.42 0 0 0-2.016 1.078l-4.129 6.194h-9.7A1.21 1.21 0 0 0 1.455 9.94v6.666Zm-2.064 2.299H1.455v7.273h7.272v-2.182H3.636Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xh09pvbbq {
  fill: var(--svg-color--91b0f2, #91b0f2);
  d: path("M23.273 12.364a3.636 3.636 0 1 0-3.636-3.636a3.636 3.636 0 0 0 3.636 3.636");
}

.xxyl10b5k {
  fill: var(--svg-color--0f46bd, #0f46bd);
  d: path("M1.455 9.939v6.667L5.7 20.974l1.815-1.944l5.455 5.455l-1.819 1.815l4.242 4.242h6.667a1.21 1.21 0 0 0 1.212-1.212v-9.7L12.364 8.727h-9.7a1.21 1.21 0 0 0-1.209 1.212");
}

.xyjtgccot {
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y6hacsbqt {
  fill: var(--svg-color--729af2, #729af2);
  d: path("m7.5 22.707l9.255-9.255l1.792 1.792L9.293 24.5Z");
}

.ynzpjdbfo {
  fill: var(--svg-color--4c80f0, #4c80f0);
  d: path("M10.772 23.02L8.98 21.228l7.776-7.775l1.792 1.792Z");
}

.z3zfb1pya {
  d: path("M3.636 23.273H1.455v7.273h7.272v-2.182H3.636Z");
}

</style>
