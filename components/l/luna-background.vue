<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="ey7nyqckj"/><path fill="url(#SVGLBjLtcgt)" class="cacmp2att"/><path fill="url(#SVGcXTQMemg)" class="t7szkjn4h"/></g><defs><linearGradient id="SVGLBjLtcgt" x1="7.645" x2="16.277" y1="6.576" y2="13.915" gradientUnits="userSpaceOnUse"><stop class="y0kuriblj"/><stop offset="1" class="udxjgzzlp"/></linearGradient><linearGradient id="SVGcXTQMemg" x1="9.058" x2="11.578" y1="15.636" y2="20.04" gradientUnits="userSpaceOnUse"><stop class="a0osbbbvn"/><stop offset="1" class="rbs-fybft"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:luna-background" /></template>
<style>
.a0osbbbvn {
  stop-color: var(--svg-color--f3be56, #f3be56);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.cacmp2att {
  d: path("M13.778 4c-.596.889-1.747 1.507-2.542 1.782a7.11 7.11 0 0 0-6.702 8.231c.64 1.956 1.969 3.289 3.8 3.391c1.91.111 3.773-.573 4.644-2.675c.702-1.69 1.938-2.182 2.467-2.285h4.11l-1-.71c-1.48-1.267-3.768-1.125-4.373-.6a3.3 3.3 0 0 1-1.857.781c-2.271 0-2.471-1.72-2.471-2.124v-.044c-.005-.463-.014-1.791 2.12-2.507a2.75 2.75 0 0 0 1.573-1.182h-.005c.454-.702.356-1.69.236-2.058");
}

.ey7nyqckj {
  fill: var(--svg-color--f2e373, #f2e373);
  d: path("M11.556 20a7.111 7.111 0 1 0 0-14.222a7.111 7.111 0 0 0 0 14.222");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rbs-fybft {
  stop-color: var(--svg-color--e04437, #e04437);
}

.t7szkjn4h {
  d: path("M17.37 16.987a7.11 7.11 0 0 1-12.81-2.831c.432 1.262 1.712 3.293 4.098 3.249c2.591-.045 3.876-1.662 4.223-2.56c.35-.89 1.222-2.08 2.555-2.4c-.547.338-1.542 1.266-1.44 2.4c.12 1.382 1.236 2.297 3.373 2.142");
}

.udxjgzzlp {
  stop-color: var(--svg-color--de3633, #de3633);
}

.y0kuriblj {
  stop-color: var(--svg-color--f5c859, #f5c859);
}

</style>
