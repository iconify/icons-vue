<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz1l0ubgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coinex" /></template>
<style>
.xz1l0ubgq {
  fill: var(--svg-color--0ead98, #0ead98);
  d: path("M12.267 21C7.157 21 3 16.96 3 12s4.157-9 9.267-9c3.55 0 6.831 2.012 8.364 5.12l.369.746l-2.591 2.515l-1.726-1.652L18.03 8.42c-1.247-1.89-3.424-3.076-5.762-3.076c-3.765 0-6.83 2.986-6.83 6.65c0 3.663 3.065 6.65 6.83 6.65c2.338 0 4.515-1.187 5.762-3.077l-4.725-4.595a1.47 1.47 0 0 0-1.037-.418c-.391 0-.755.148-1.036.418a1.407 1.407 0 0 0 0 2.033c.276.27.645.418 1.036.418c.392 0 .756-.148 1.037-.418l.419-.413l1.73 1.652l-.424.413a3.93 3.93 0 0 1-2.762 1.111a3.95 3.95 0 0 1-2.762-1.111a3.705 3.705 0 0 1 0-5.342a3.94 3.94 0 0 1 2.762-1.112a3.95 3.95 0 0 1 2.762 1.112L21 15.118l-.37.747C19.099 18.988 15.813 21 12.268 21");
}

</style>
