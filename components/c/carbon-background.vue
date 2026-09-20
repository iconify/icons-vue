<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="y9cegcu0k"/><path class="k0dwi6mzd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:carbon-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k0dwi6mzd {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.962 12.236c-.103 1.285-.88 3.53-3.407 3.53c-1.788 0-3.53-1.822-4.781-2.951c-.16-.156-.48-.542-.48-.814c0-.273.32-.66.48-.815c1.252-1.129 2.997-2.95 4.781-2.95c2.494 0 3.285 2.24 3.403 3.53h3.571v.47zm-.795-.47c.08 0 .141-.071.127-.151c-.16-1.078-.861-2.909-2.824-2.909c-.804 0-1.736.72-2.193 1.036a.1.1 0 0 0-.039.067a.1.1 0 0 0 .025.074l1.68 1.882zm-4.461 0c.117 0 .174-.147.094-.236l-1.14-1.318c-.513.433-1.285.98-1.661 1.553zm4.593.62c.014-.08-.085-.15-.16-.15c-.151 0-.255.061-.363.17l-2.555 2.87q.129.02.25.019c1.99 0 2.682-1.836 2.828-2.908m-1.793.4c.164-.174.047-.55-.188-.55H8a17.5 17.5 0 0 0 3.53 2.837z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9cegcu0k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06m0 .47a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

</style>
