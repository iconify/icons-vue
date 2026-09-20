<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="dzz5wybqk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flame-background" /></template>
<style>
.dzz5wybqk {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.56 19.556c-2.652-1.93-3.653-5.006-1.934-8.262c.113-.217.454-.14.52.093c.254.83.765 1.249.765 1.249c-.165-.377-.795-4.454 2.245-6.328c.175-.108.392.052.36.259c-.133 1.042-.237 3.282 1.56 2.652c1.63-.568.459-3.55-.14-4.84c-.103-.212.108-.444.325-.362c3.613 1.497 6.43 3.922 5.414 8.324c.268.052 1.15-.103 1.651-.836c.13-.19.434-.2.496.021c.5 1.693 1.238 6.126-2.7 8.474a3.05 3.05 0 0 0-.815-1.125c-.041-.031-.077-.02-.108.02c-.155.212-.671.862-1.182.904c-.929.072-1.455-.955-1.223-2.075c.026-.124-.088-.242-.207-.206c-1.476.48-1.857 1.47-1.857 1.47c-.64-.52-1.203-1.496-1.084-3.695c.01-.165-.196-.247-.29-.103c-.572.867-1.712 2.772-1.8 4.366z");
}

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

</style>
