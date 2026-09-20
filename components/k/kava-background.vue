<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="re1gnfb5u"/><path class="ff7bt8b8s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kava-background" /></template>
<style>
.ff7bt8b8s {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.603 10.399h.8l-1.8 4h-.8l-1.801-4h.8l1.4 3.2zm-10.803 4V9.6H4v4.8zm2.2 0L5.2 12L7 9.6h1.001l-1.8 2.4L8 14.4zm3.094-4c-.88 0-1.565.48-1.613 1.2h.784c.072-.34.528-.4.829-.4c.296 0 .708.14.708.552V12h-.997c-.884 0-1.404.532-1.404 1.208c0 .713.532 1.193 1.32 1.193a1.4 1.4 0 0 0 1.08-.416v.416h.8v-2.713c0-.78-.6-1.288-1.508-1.288m.708 2.204v.24c-.052.52-.4.729-.945.757c-.316.016-.592-.144-.592-.4s.188-.489.64-.52zm7.69-2.204c-.877 0-1.56.48-1.613 1.2h.788c.072-.34.528-.4.825-.4s.712.14.712.552V12h-1c-.889 0-1.4.532-1.4 1.208c0 .713.531 1.193 1.316 1.193a1.4 1.4 0 0 0 1.08-.416v.416h.8v-2.713c0-.78-.6-1.288-1.508-1.288m.712 2.204v.24c-.052.52-.4.729-.945.757c-.32.016-.592-.144-.592-.4s.188-.489.64-.52z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.re1gnfb5u {
  fill: var(--svg-color--ff564f, #ff564f);
  d: path("M24 0H0v24h24z");
}

</style>
