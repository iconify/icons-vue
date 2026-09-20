<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="y9cegcu0k"/><path class="tn-r3fbga"/><path clip-rule="evenodd" class="xdvlqe9pw"/><path class="vdo7eccjx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aag-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tn-r3fbga {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 6.353a5.6 5.6 0 0 0-3.313 1.054l-.216.17L8 7.293l.423-.254a6.118 6.118 0 0 1 8.47 8.63l-.362-.273A5.62 5.62 0 0 0 17.647 12A5.633 5.633 0 0 0 12 6.353M7.45 8.63A5.6 5.6 0 0 0 6.353 12A5.633 5.633 0 0 0 12 17.647a5.62 5.62 0 0 0 3.365-1.092l.273.367a6.116 6.116 0 0 1-8.55-8.565z");
}

.vdo7eccjx {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.61 7.944L6.278 6.612l.33-.33L7.943 7.61l-.33.334zm9.778 9.779l-1.331-1.332l.33-.334l1.335 1.332zm-3.976-9.864v1.68l1.882-1.012v5.318l-2.353-1.134v-2.386l-1.882 1.012v4.33l-2.353-1.135v-4.395zm-.47 1.93V8.612l-3.765 1.821v3.803l1.412.682v-3.859zm.47.282v2.343l1.412.683V9.318l-1.412.758z");
}

.xdvlqe9pw {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.764 8.235a.47.47 0 1 0 0-.94a.47.47 0 0 0 0 .94m0 .47a.941.941 0 1 0 0-1.882a.941.941 0 0 0 0 1.883m8.471 8a.47.47 0 1 0 0-.94a.47.47 0 0 0 0 .94m0 .471a.941.941 0 1 0 0-1.882a.941.941 0 0 0 0 1.882");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
