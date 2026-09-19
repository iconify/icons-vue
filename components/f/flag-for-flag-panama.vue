<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="daz-7nbru"/><path class="uumptzb3e"/><path class="b4jcmu9li"/><path class="w-mxt2b5c"/><path class="a61br9bcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-panama" /></template>
<style>
.a61br9bcm {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("m19.993 19.778l-4.01.007l-1.244-4.056l-1.236 4.056l-4.01-.007l3.248 2.472l-1.254 4.03l3.26-2.504l3.265 2.504l-1.26-4.03z");
}

.b4jcmu9li {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H32v22h32V21c0-6.075-3.373-11-10-11");
}

.daz-7nbru {
  fill: var(--svg-color--2b3990, #2b3990);
  d: path("M0 32v11c0 6.075 3.373 11 10 11h22V32z");
}

.uumptzb3e {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M32 10H10C3.373 10 0 14.925 0 21v11h32zm0 44h22c6.627 0 10-4.925 10-11V32H32z");
}

.w-mxt2b5c {
  fill: var(--svg-color--cb0000, #cb0000);
  d: path("m54.24 41.527l-4.01.008l-1.241-4.056l-1.236 4.056l-4.01-.008L46.991 44l-1.254 4.03l3.26-2.505l3.265 2.505l-1.26-4.03z");
}

</style>
