<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wssn-o4bk"/><path class="b4yxu8bqx"/><path class="bqiirrz0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:brown-mushroom" /></template>
<style>
.b4yxu8bqx {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("m34.666 11.189l-.001-.002a17.9 17.9 0 0 0-4.208-6.182h-.003A17.92 17.92 0 0 0 18 0A17.96 17.96 0 0 0 0 18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4c0-2.417-.48-4.713-1.334-6.811");
}

.bqiirrz0t {
  fill: var(--svg-color--cc927a, #cc927a);
  d: path("M11.771 10.934c1.546-1.547 1.86-3.74.7-4.9s-3.353-.846-4.9.7c-1.546 1.546-1.86 3.74-.7 4.9s3.354.846 4.9-.7");
}

.wssn-o4bk {
  fill: var(--svg-color--f2c994, #f2c994);
  d: path("M27 33c0 2.209-1.791 3-4 3H13c-2.209 0-4-.791-4-3s3-7 3-13s12-6 12 0s3 10.791 3 13");
}

</style>
