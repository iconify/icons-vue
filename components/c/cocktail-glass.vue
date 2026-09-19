<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wh4ipabhf"/><path class="nds850gup"/><path class="prja4tx5s"/><path class="qrxtqhb6o"/><path class="fankyab0g"/><path class="da5csubbk"/><path class="kkjomhbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cocktail-glass" /></template>
<style>
.da5csubbk {
  fill: var(--svg-color--a1b8c7, #a1b8c7);
  d: path("M59 18.6H5S24.1 40 30.8 42.8c0 2.1-.2 9.7-.9 13c-3.7 3.2-11.4 5.4-11.5 5.4c-.2.1-.3.3-.2.5c0 .2.2.4.3.4h26.9c.2 0 .3-.2.3-.4s-.1-.4-.2-.5c-.1 0-7.8-2.2-11.5-5.4c-.7-3.3-.8-10.9-.8-13C40 39.9 59 18.6 59 18.6M32 40.7c-4.1 0-21.9-19.8-21.9-19.8h43.7c.1 0-17.7 19.8-21.8 19.8");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.fankyab0g {
  fill: var(--svg-color--ce114b, #ce114b);
  d: path("M36.5 29c-.8 1.3-.7 2.8.3 3.4s2.4 0 3.2-1.2c.8-1.3.7-2.8-.3-3.4c-.9-.6-2.4 0-3.2 1.2");
}

.kkjomhbgd {
  fill: var(--svg-color--f3ffd2, #f3ffd2);
  d: path("M49.4 22.7S35.3 38.5 32 38.5S14.6 22.7 14.6 22.7z");
  opacity: var(--svg-opacity--0-7, 0.7);
}

.nds850gup {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M45.5 17.9c-.3 2.4-3.2 3.9-6.5 3.5c-3.2-.4-5.6-2.7-5.3-5c.3-2.4 3.2-3.9 6.5-3.5s5.6 2.6 5.3 5");
}

.prja4tx5s {
  fill: var(--svg-color--ce114b, #ce114b);
  d: path("M38.4 16.9c-.2 1.5-1.3 2.6-2.4 2.4c-1.1-.1-1.9-1.5-1.7-2.9c.2-1.5 1.3-2.6 2.4-2.4c1.1.1 1.9 1.5 1.7 2.9");
}

.qrxtqhb6o {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M30.4 25.3c-1.3 2-.1 5 2.7 6.7s6.1 1.4 7.4-.6s.1-5-2.7-6.7c-2.8-1.6-6.1-1.4-7.4.6");
}

.wh4ipabhf {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M45.7 3.3c.2-.6 0-1.2-.4-1.3s-.9.2-1.1.8L31.7 37l.8.3z");
}

</style>
