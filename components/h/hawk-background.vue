<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="qlx8a3bhi"/><path class="r59_5_boc"/><path clip-rule="evenodd" class="yx6dlg-lj"/><path class="nc1o9kp7u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hawk-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.nc1o9kp7u {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.233 8.724a4.17 4.17 0 0 0-2.758.334q.25-.038.504-.056c.103 0 .94.32 1.407.282c.348-.033.574-.338.658-.513a.06.06 0 0 1 .047-.033zm-1.826 11.253c-1.515-2.085-1.647-5.868 1.543-7.84c-2.004 3.021.344 5.6 2.622 7.021a7.97 7.97 0 0 1-4.165.82m3.36-11.564c-.4.08-1.082.339-1.242.974c-.278 1.069-.47 2.217-.56 2.739a6 6 0 0 1 5.713-.33c-.32-1.246-1.699-2.757-3.91-3.383");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qlx8a3bhi {
  fill: var(--svg-color--0d3137, #0d3137);
  d: path("M24 0H0v24h24z");
}

.r59_5_boc {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.654 17.949a8 8 0 0 1-2.475-4.259c.795-1.223 2.73-3.774 6.423-4.668l-.141.094c-.847.518-2.278 1.412-3.233 3.087c-.979 1.713-1.11 3.859-.574 5.746");
}

.yx6dlg-lj {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0 0a7.96 7.96 0 0 0 3.576-.842c-2.287-1.422-4.63-4-2.62-7.022a5.99 5.99 0 0 1 5.722-.338c-.33-1.261-1.732-2.796-3.991-3.403c-.767-.207-1.266-.47-1.412-.579l-.014-.009c-.57-.395-.81-.56-.983-.588c-1.106-.127-2.4.216-3.36.583a9.04 9.04 0 0 0-4.909 4.593A8 8 0 0 0 12 20");
}

</style>
