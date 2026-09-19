<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xpog3kbzu"/><path class="i1bvsdp9h"/><path class="bve3gqbiu"/><path class="mwq-17box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-united-arab-emirates" /></template>
<style>
.bve3gqbiu {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M60.3 22H22v20h38.3c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10");
}

.i1bvsdp9h {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 2c-3.5 0-6.9.6-10 1.7V22h38.3C56.2 10.4 45.1 2 32 2");
}

.mwq-17box {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M22 42v18.3c3.1 1.1 6.5 1.7 10 1.7c13.1 0 24.2-8.3 28.3-20z");
}

.xpog3kbzu {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M2 32c0 13.1 8.4 24.2 20 28.3V3.7C10.4 7.8 2 18.9 2 32");
}

</style>
