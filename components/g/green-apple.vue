<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="msmsz-bsr"/><path class="bsdhsjmvd"/><path class="gmv4z47ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:green-apple" /></template>
<style>
.bsdhsjmvd {
  fill: var(--svg-color--947151, #947151);
  d: path("M33.3 16.3h-2.6c0-4.3 2.4-11.6 12-11.6v2.6c-8.7 0-9.4 8.2-9.4 9");
}

.gmv4z47ms {
  fill: var(--svg-color--8cc63e, #8cc63e);
  d: path("M32 15.8C24.7 8.4 3 8.1 3 29.3C3 42.7 18.8 62 25.7 62c3.1 0 4.2-2 6.1-2c1.8 0 2.4 1.9 6.4 1.9C45.1 62 61 42.8 61 29.3C61 8.1 39.3 8.4 32 15.8");
}

.msmsz-bsr {
  fill: var(--svg-color--64892f, #64892f);
  d: path("M31.4 4.9c1.1 2.5-.5 10.9-.5 10.9s-7.5-4.4-8.6-6.9s0-5.4 2.5-6.5s5.5 0 6.6 2.5");
}

</style>
