<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r055oqb9k"/><path class="bzwv7ujhf"/><path class="tn4etjbsu"/><path class="yqojpjbwc"/><path class="dmtbxsbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:clipboard" /></template>
<style>
.bzwv7ujhf {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
  d: path("M51.893 53.54c0 2.272-2.026 4.111-4.529 4.111H18.471c-2.499 0-4.529-1.839-4.529-4.111V16.48c0-2.271 2.03-4.112 4.529-4.112h28.892c2.503 0 4.529 1.841 4.529 4.112v37.06z");
}

.dmtbxsbpl {
  fill: var(--svg-color--34484c, #34484c);
  d: path("M35.13 8.978c0 .274-.234.496-.53.496h-3.373c-.292 0-.53-.222-.53-.496V4.511c0-.273.238-.496.53-.496H34.6c.295 0 .53.223.53.496zM19.654 19.432h25.702c1.729 0 1.729-2.43 0-2.43H19.654c-1.725 0-1.725 2.43 0 2.43m0 4.933h25.702c1.729 0 1.729-2.428 0-2.428H19.654c-1.725 0-1.725 2.428 0 2.428m0 5.043h25.702c1.729 0 1.729-2.43 0-2.43H19.654c-1.725 0-1.725 2.43 0 2.43m0 4.932h25.702c1.729 0 1.729-2.43 0-2.43H19.654c-1.725 0-1.725 2.43 0 2.43m0 17.83h11.829c1.725 0 1.725-2.43 0-2.43H19.654c-1.725 0-1.725 2.43 0 2.43");
}

.r055oqb9k {
  fill: var(--svg-color--b97f44, #b97f44);
  d: path("M59.834 58.39c0 3.222-2.875 5.833-6.428 5.833H12.427C8.879 64.223 6 61.611 6 58.39V5.83C6 2.608 8.879-.001 12.427-.001h40.979c3.553 0 6.428 2.609 6.428 5.831z");
}

.tn4etjbsu {
  fill: var(--svg-color--fff, #fff);
  d: path("M51.893 50.643c0 2.269-2.026 4.112-4.529 4.112H18.471c-2.499 0-4.529-1.844-4.529-4.112v-37.06c0-2.271 2.03-4.11 4.529-4.11h28.892c2.503 0 4.529 1.839 4.529 4.11v37.06z");
}

.yqojpjbwc {
  fill: var(--svg-color--d0d2d3, #d0d2d3);
  d: path("M45.523 11.707c0 .273-1.347.496-3.01.496h-19.2c-1.664 0-3.01-.223-3.01-.496V7.239c0-.274 1.347-.496 3.01-.496h19.2c1.66 0 3.01.222 3.01.496z");
}

</style>
