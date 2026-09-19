<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tboqicctp"/><path class="udyd--buf"/><path class="te4i29waz"/><path class="t0oipwkvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-suriname" /></template>
<style>
.t0oipwkvy {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("m39.39 30.15l-5.689.01l-1.763-5.755l-1.748 5.755l-5.692-.01l4.612 3.496l-1.79 5.714l4.627-3.55l4.627 3.55l-1.79-5.714z");
}

.tboqicctp {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-3H0zm54-33H10C3.373 10 0 14.925 0 21v3h64v-3c0-6.075-3.373-11-10-11");
}

.te4i29waz {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 21h64v3H0zm0 19h64v3H0z");
}

.udyd--buf {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 24h64v16H0z");
}

</style>
