<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="o520d9bvh"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aurabal-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.o520d9bvh {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.027 8.617v-.015c0-.51-1.338-.956-3.292-1.174c.465.313.876.705 1.22 1.159l.075.015l-.053.011a20 20 0 0 1-3.939.343c-1.562 0-2.956-.133-3.95-.343l-.027-.007h-.02l.066-.016a5.2 5.2 0 0 1 1.219-1.162c-1.943.218-3.28.663-3.28 1.174c0 .644 2.899 1.15 4.857 1.295c.434.03 1.12.03 1.12.03c.244.012.686 0 1.12-.03c1.966-.137 4.857-.644 4.884-1.28m-.572 2.709q-.213-.045-.426-.084a5.5 5.5 0 0 0-.221-1.014c1.935.317 3.192.82 3.192 1.39v.02c-.046.952-3.611 1.722-8 1.722c-4.42 0-8-.781-8-1.741v-.02c.027-.567 1.303-1.066 3.261-1.382c-.103.324-.18.663-.221 1.01q-.537.099-1.067.24q-.274.076-.491.152q.74.258 1.512.38c1.326.249 3.075.4 5.006.4a28.4 28.4 0 0 0 5.459-.487a9 9 0 0 0 1.06-.293a9 9 0 0 0-1.06-.293zM7.558 14.38c-.94.232-1.512.54-1.512.876v.02c.05.715 2.716 1.294 5.992 1.294s5.943-.579 5.989-1.295v-.019c0-.339-.572-.648-1.52-.876a5.7 5.7 0 0 1-.53.865l.057.011l-.076.015h-.015c-.99.206-2.366.34-3.905.34s-2.914-.134-3.908-.336h-.02l-.003-.008c-.023 0-.046-.007-.065-.01l.046-.012a5 5 0 0 1-.53-.865");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
