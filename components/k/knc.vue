<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="fep4f1slk"><path class="y0j4pebqu"/><path class="olu67g6ri"/><path class="crm1zc0bs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:knc" /></template>
<style>
.crm1zc0bs {
  d: path("M12.354 20.784a.266.266 0 0 0 .286.215a.26.26 0 0 0 .122-.044l4.974-3.309a.262.262 0 0 0-.006-.442l-6.35-3.97a.264.264 0 0 0-.401.273zm5.593-4.69a.264.264 0 0 0 .405-.223V8.26a.264.264 0 0 0-.394-.23l-6.414 3.601a.264.264 0 0 0-.01.454z");
}

.fep4f1slk {
  fill: var(--svg-color--31cb9e, #31cb9e);
}

.olu67g6ri {
  d: path("M10.78 3.383a.265.265 0 0 1 .418.262l-1.604 8.129a.3.3 0 0 0 0 .1l1.61 8.52a.265.265 0 0 1-.408.267l-5.03-3.346a.26.26 0 0 1-.119-.22v-9.74c0-.083.04-.162.106-.211z");
}

.y0j4pebqu {
  d: path("M12.78 3.053a.265.265 0 0 0-.418.16l-1.387 7.029a.26.26 0 0 0 .106.264a.26.26 0 0 0 .284.016l6.159-3.459a.26.26 0 0 0 .134-.212a.26.26 0 0 0-.106-.228z");
}

</style>
