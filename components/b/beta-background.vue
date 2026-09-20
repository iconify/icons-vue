<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG22nglc6X)" class="r4i437pya"/><path clip-rule="evenodd" class="f6kgjwb0g"/></g><defs><linearGradient id="SVG22nglc6X" x1="19.571" x2="5.429" y1="9.429" y2="17.428" gradientUnits="userSpaceOnUse"><stop class="qm3q7nxtu"/><stop offset="1" class="dnajc-bko"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:beta-background" /></template>
<style>
.dnajc-bko {
  stop-color: var(--svg-color--ad8bd4, #ad8bd4);
}

.f6kgjwb0g {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.657 17.657A8 8 0 1 1 6.343 6.344a8 8 0 0 1 11.314 11.313m-3.878-8.98c-.052-.065.01-.16.09-.136c1.157.325 1.91.857 1.91 1.468c0 .993-2.01 1.793-4.485 1.793c-1.614 0-3.03-.338-3.816-.856c-.066-.038-.029-.137.047-.123c.597.118 1.27.18 1.976.18c2.475 0 4.485-.8 4.485-1.789a.87.87 0 0 0-.207-.536m.885 3.125c-.062-.075.014-.183.108-.16c1.346.382 2.226 1.007 2.226 1.718c0 1.153-2.344 2.094-5.238 2.094c-1.887 0-3.544-.4-4.461-1.002c-.08-.047-.033-.16.061-.142c.692.137 1.478.212 2.306.212c2.894 0 5.238-.936 5.238-2.094c0-.216-.085-.428-.24-.626");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qm3q7nxtu {
  stop-color: var(--svg-color--cd9cbc, #cd9cbc);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
