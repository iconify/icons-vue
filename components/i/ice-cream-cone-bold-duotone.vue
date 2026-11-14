<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="mt62r6b0p"/><path class="exzwhzb0h"/></g><path clip-rule="evenodd" class="f-kx82bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ice-cream-cone-bold-duotone" /></template>
<style>
.exzwhzb0h {
  d: path("M16.123 12.5797L8.90723 15.0104L7.25 11.1022H16.75L16.123 12.5797Z");
}

.f-kx82bze {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 8.85217C5.25 5.12427 8.2721 2.10217 12 2.10217C15.7279 2.10217 18.75 5.12427 18.75 8.85217C18.75 10.3022 18.1 11.1022 17 11.1022H7C5.9 11.1022 5.25 10.3022 5.25 8.85217Z");
}

.mt62r6b0p {
  d: path("M12.5859 20.9215C12.3099 21.5723 12.1715 21.8981 12 21.8981C11.8285 21.8981 11.69 21.5722 11.4141 20.9215L9.49414 16.3951L15.3398 14.4264L12.5859 20.9215Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
