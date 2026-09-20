<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGB6QO3dIX)" class="beea8ldsd"/><path fill="url(#SVGB6QO3dIX)" clip-rule="evenodd" class="nfq6txb4n"/><defs><linearGradient id="SVGB6QO3dIX" x1="7.179" x2="16.661" y1="4.607" y2="19.071" gradientUnits="userSpaceOnUse"><stop class="uvhtnccri"/><stop offset=".38" class="jrfu1k1kl"/><stop offset=".74" class="ebrro4btw"/><stop offset="1" class="ffhlweo6a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cummies" /></template>
<style>
.beea8ldsd {
  d: path("M13.901 6.937h-3.026l.776-2.25h-1.423L6.094 14.813h1.468l1.063-2.25h3.071l-1.035 2.402L8.496 16.5h-4.67L3 14.964L7.106 4.536L9.187 3h4.714l.912 1.536z");
}

.ebrro4btw {
  stop-color: var(--svg-color--f0a, #f0a);
}

.ffhlweo6a {
  stop-color: var(--svg-color--d517d1, #d517d1);
}

.ft5dv1b6b {
  fill: none;
}

.jrfu1k1kl {
  stop-color: var(--svg-color--fd00b3, #fd00b3);
}

.nfq6txb4n {
  fill-rule: evenodd;
  d: path("m18.024 17.316l-1.62.82l.822 1.238l-.71 1.626h-2.93l.945-2.25H13.07L12.163 21H9.187l5.108-12.375h5.636L21 10.251zm-3.729-1.35c-.023-.13-.045-.231-.04-.287c.023-.175.04-.214.338-.36c-.259-.113-.208-.433-.146-.574c-.163.04-.534.158-.754.32c-.073-.663.478-.978.765-1.057c-.067-.107-.084-.607.388-1.772c.473-1.158 1.705-1.766 2.262-1.923c.303.534.793 1.89.32 3.048c-.472 1.165-.844 1.496-.967 1.52c.157.27.343.905-.18 1.304a2.7 2.7 0 0 0-.338-.787c-.056.14-.242.399-.517.28c.118.327.106.366 0 .507c-.04.045-.124.096-.237.169c-.236.14-.579.349-.826.709a2.8 2.8 0 0 0-.068-1.097");
}

.uvhtnccri {
  stop-color: var(--svg-color--f000e1, #f000e1);
}

</style>
