<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwI8e8c9S)" class="gp74io94i"/><path fill="url(#SVGwI8e8c9S)" class="anh7vv-1y"/><path fill="url(#SVGRgQfTcIO)" class="cd79g7j1h"/><defs><linearGradient id="SVGwI8e8c9S" x1="14.573" x2="14.573" y1="9.454" y2="20.997" gradientUnits="userSpaceOnUse"><stop class="ozqlykbuu"/><stop offset="1" class="tshln8pzh"/></linearGradient><linearGradient id="SVGRgQfTcIO" x1="14.572" x2="14.572" y1="9.454" y2="20.997" gradientUnits="userSpaceOnUse"><stop class="ozqlykbuu"/><stop offset="1" class="tshln8pzh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gel" /></template>
<style>
.anh7vv-1y {
  d: path("M6.947 10.823a.51.51 0 0 0-.543.243a.5.5 0 0 0-.064.2a.45.45 0 0 0 .051.237l4.9 9.38a.219.219 0 0 0 .385 0l5.908-10.353a.67.67 0 0 0 .077-.34a.596.596 0 0 0-.484-.57a8.4 8.4 0 0 0-2.424-.13c-1.04.109-1.904.428-2.799.762l-.139.052a9.3 9.3 0 0 1-3.103.72c-.566.016-1.106-.046-1.765-.206z");
}

.cd79g7j1h {
  d: path("M11.485 10.55a.26.26 0 0 1 .17-.246l.144-.052c.95-.375 1.942-.63 2.954-.761a8.4 8.4 0 0 1 2.424.128a.6.6 0 0 1 .483.618c0 .103-.03.2-.077.293l-5.907 10.354a.21.21 0 0 1-.19.113z");
}

.ft5dv1b6b {
  fill: none;
}

.gp74io94i {
  d: path("M16.858 8.235c0 .247-.232.422-.484.396a8.2 8.2 0 0 0-1.708 0c-1.153.118-2.11.504-2.99.834l-.16.056c-.936.35-1.8.644-2.825.67a6 6 0 0 1-1.333-.124a1.09 1.09 0 0 1-.828-.85a5.213 5.213 0 1 1 10.328-.987z");
}

.ozqlykbuu {
  stop-color: var(--svg-color--ffc4a4, #ffc4a4);
}

.tshln8pzh {
  stop-color: var(--svg-color--fe858c, #fe858c);
}

</style>
