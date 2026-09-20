<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGwGbkicpS)" class="h5phnw3lc"/><path fill="url(#SVGmPdo5DkG)" class="kawxq-jjz"/><path class="z6ca8n5fi"/><path fill="url(#SVGUsPAyjgK)" class="ruiyn8dbv"/><path fill="url(#SVGaflXFeyC)" class="g_fop9b6q"/><path fill="url(#SVGewXdxcQL)" class="m_52egu5v"/><defs><linearGradient id="SVGwGbkicpS" x1="20.353" x2="5.124" y1="3.639" y2="18.257" gradientUnits="userSpaceOnUse"><stop class="tjv6vpb2b"/><stop offset="1" class="sgzl26bmm"/></linearGradient><linearGradient id="SVGmPdo5DkG" x1="21.052" x2="2.642" y1="7.343" y2="8.971" gradientUnits="userSpaceOnUse"><stop class="vcup_ybvq"/><stop offset="1" class="tzhny7i5o"/></linearGradient><linearGradient id="SVGUsPAyjgK" x1="3.591" x2="22.176" y1="3.528" y2="19.098" gradientUnits="userSpaceOnUse"><stop class="ea-f0szgd"/><stop offset=".54" class="ugezfd0dp"/><stop offset="1" class="yqob8umgg"/></linearGradient><linearGradient id="SVGaflXFeyC" x1="3.593" x2="22.162" y1="3.54" y2="19.075" gradientUnits="userSpaceOnUse"><stop class="ea-f0szgd"/><stop offset=".54" class="ugezfd0dp"/><stop offset="1" class="yqob8umgg"/></linearGradient><linearGradient id="SVGewXdxcQL" x1="11.485" x2="4.593" y1="16.618" y2="19.735" gradientUnits="userSpaceOnUse"><stop class="ii6m1jdul"/><stop offset="1" class="xb0-9b9mg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:launch" /></template>
<style>
.ea-f0szgd {
  stop-color: var(--svg-color--51a7e8, #51a7e8);
}

.ft5dv1b6b {
  fill: none;
}

.g_fop9b6q {
  d: path("M8.852 9.86c1.877.36 2.695.952 2.875 1.204c-.684.411-1.841.74-2.417.669c-3.878-.443-4.181-2.834-4.181-3.076c.9.556 1.378.761 3.723 1.204");
}

.h5phnw3lc {
  d: path("M14.582 8.611c.812-.771 3.929-2.006 5.39-2.525c-.993.514-3.158 1.697-3.883 2.345c-.72.648-1.163 1.98-1.291 2.566c.128.005.226.041.226.14c-.432 4.062-3.872 4.936-4.947 5.235c2.345-1.518 2.797-2.803 2.746-3.256c-.103.062-.288.17-.376.17c1.163-3.559 1.122-3.703 2.135-4.675");
}

.ii6m1jdul {
  stop-color: var(--svg-color--d265ca, #d265ca);
}

.kawxq-jjz {
  d: path("M14.207 6.096c-2.54.288-2.639 2.242-2.392 3.075c.617-1.784 1.389-2.252 1.918-2.252c.535 0 1.05.421 1.471.421c.427 0 .834-.267.92-.421c-.385-.623-1.408-.885-1.917-.823");
}

.m_52egu5v {
  d: path("M10.076 13.553c.5-.16 1.332-.93 1.636-1.296c.154.679-.936 1.635-1.337 1.913c-.396.278-1.512 1.234-1.4 1.337c.222.196 1.646-.566 1.847-.627q.13-.044.268-.052c.05 0 .087.016.087.052c-1.533 1.178-2.088 1.697-2.536 2.314c-.442.617-.329 1.553-.555 2.057A3.03 3.03 0 0 1 5.463 21c-.026-.088-.051-.35.072-.72a2.4 2.4 0 0 0 .144-.695c0-.072 0-.128-.036-.128c-.247 0-.71.586-.91 1.028c-.052-.431-.154-1.331-.154-1.614c0-1.692 1.42-2.988 2.134-3.425l3.363-2.33z");
}

.ruiyn8dbv {
  d: path("M8.22 6.754C5.206 5.417 4.157 3.694 4.029 3v1.466c0 .596.334 1.255.56 1.543c.221.293.448.745.36.745a2.3 2.3 0 0 1-.586-.154c.494 1.733 2.556 2.484 4.304 2.793c1.749.308 3.271 1.074 3.605 1.321c-.02-.535-1.296-2.7-4.052-3.96");
}

.sgzl26bmm {
  stop-color: var(--svg-color--ce65c7, #ce65c7);
}

.tjv6vpb2b {
  stop-color: var(--svg-color--d86582, #d86582);
}

.tzhny7i5o {
  stop-color: var(--svg-color--be73d1, #be73d1);
}

.ugezfd0dp {
  stop-color: var(--svg-color--9386f2, #9386f2);
}

.vcup_ybvq {
  stop-color: var(--svg-color--e064ab, #e064ab);
}

.xb0-9b9mg {
  stop-color: var(--svg-color--928af1, #928af1);
}

.yqob8umgg {
  stop-color: var(--svg-color--ce6df3, #ce6df3);
}

.z6ca8n5fi {
  fill: var(--svg-color--c771bc, #c771bc);
  d: path("M13.373 7.958c0-.077.185-.252.278-.33c.087.068.272.217.272.284c0 .077-.185.231-.329.231c-.149 0-.221-.092-.221-.185");
}

</style>
