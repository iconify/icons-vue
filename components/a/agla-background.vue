<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ro_znhb0l"/><path clip-rule="evenodd" class="ljt7o9z2v"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:agla-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ljt7o9z2v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.965 12.599c-1.498.216-3.189 1.714-3.965 2.677a9.62 9.62 0 0 0 15.982.554l.018-.223c-1.203-1.925-2.906-2.81-3.61-3.008c1.005-2.606 2.352-8.425-.355-8.425c-2.708 0-3.454 4.014-3.557 6.318h-.601c-.103-2.304-.957-6.318-3.61-6.318c-2.763 0-1.306 5.819-.302 8.425m4.46 4.512a.3.3 0 1 0-.603 0c0 .26-.06.494-.18.662a.48.48 0 0 1-.421.241c-.524 0-.602-.24-.602-.3a.3.3 0 1 0-.602 0c0 .54.524.902 1.204.902c.42 0 .728-.217.926-.512c.18.265.47.512.879.512c.68 0 1.203-.361 1.203-.903a.301.301 0 0 0-.601 0c0 .06-.079.301-.602.301c-.15 0-.295-.096-.421-.3a1.4 1.4 0 0 1-.18-.602");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ro_znhb0l {
  fill: var(--svg-color--ababab, #ababab);
  d: path("M24 0H0v24h24z");
}

</style>
